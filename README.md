# Rhuuts asset store

Image and video files served over HTTPS so Instagram's publishing API can fetch them.
Instagram pulls media from a URL and does not authenticate, so these files have to be
reachable without a login. That is the only reason this repository is public.

Filenames are opaque on purpose. Nothing here says what is scheduled, when it posts, or
what the caption is. That lives in the private publisher repository.

Only files that Instagram needs to fetch belong here. Brand source files, pack artwork
and working images stay out of it.

Do not delete a file that is still referenced by an unpublished entry, or that post will
fail when its slot comes round.
