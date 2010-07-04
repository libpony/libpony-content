libpony content repository
==========================

What is libpony?
----------------

libpony is a project aiming at providing an alternative aspect of
documentation for the django community. If you know the site listapart and
the django advent project, think about a combination of these two. Now add
translations and localizations into the mix and you know what kind of content
libpony is all about.

libpony also lives from your contribution. All content lives inside a git
repository on github which you can fork make pull requests when you want your
article to be part of the library. For details regarding this process please
stay tuned. The basic stuff is still work in progress :-) There is just one
thing for certain: The license.

Authors submitting work to this project by sending one of the editors a
pull-request or a patch agree that all their work is placed under a Creative
Commons (Share alike, non-commercial) license. Every change on the files is
documented thanks to git so it should also always be clear who contributed
what :-)

Folder structure
----------------

This repository contains the articles published on libpony as well as curated
tag-pages, so the structure is pretty simple: Articles belong into the
articles "folder" and tag-pages into the "tags" folder. Each article and page
furthermore has its own folder which contains an "index.<lang>.<slug>.rst" and
a "metadata.<lang>.json" file. You can get a sample of what each of these
files should look like by creating a new article using libponytk's
"create_article" command.
