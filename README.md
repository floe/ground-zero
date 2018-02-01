ground-zero
===========

testing repo. may be nuked at any time.

To also clone the submodule, run `git submodule update --init --recursive` after initial clone, or clone directly with `git clone --recursive ...`.

To create new files in a repo through an external tool, use something like `curl -i -X PUT -H 'Authorization: token xxxx' -d '{"path": "foo.bar", "message": "curl test", "committer": {"name": "Florian Echtler", "email": "floe@butterbrot.org"}, "content": "Zm9vYmFyYmF6Cg==", "branch": "master"}' https://api.github.com/repos/floe/ground-zero/contents/foo.bar`
