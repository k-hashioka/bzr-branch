
bzr-branch info:

	https://github.com/k-hashioka/bzr-branch.git :

		Create a new repository on the command line:
			$ touch README.md
			$ git init
			$ git add README.md
			$ git commit -m "first commit"
			$ git remote add origin https://github.com/k-hashioka/bzr-branch.git
			$ git push -u origin master

		Push an existing repository from the command line:
			$ git remote add origin https://github.com/k-hashioka/bzr-branch.git
			$ git push -u origin master

	git@github.com:k-hashioka/bzr-branch.git :

		Create a new repository on the command line:
			$ touch README.md
			$ git init
			$ git add README.md
			$ git commit -m "first commit"
			$ git remote add origin git@github.com:k-hashioka/bzr-branch.git
			$ git push -u origin master

		Push an existing repository from the command line:
			$ git remote add origin git@github.com:k-hashioka/bzr-branch.git
			$ git push -u origin master

$ bzr log --show-ids 

	------------------------------------------------------------
	revno: 2
	revision-id: k.hashioka@gmail.com-20121106014848-8hzxbvt08a0cnx2v
	parent: k.hashioka@gmail.com-20121106013837-lgh4b8sz3nz7mlk4
	committer: Kuniharu Hashioka <k.hashioka@gmail.com>
	branch nick: bzr-branch
	timestamp: Tue 2012-11-06 10:48:48 +0900
	message:
	  mod: README.txt
	------------------------------------------------------------
	revno: 1
	revision-id: k.hashioka@gmail.com-20121106013837-lgh4b8sz3nz7mlk4
	committer: Kuniharu Hashioka <k.hashioka@gmail.com>
	branch nick: bzr-branch
	timestamp: Tue 2012-11-06 10:38:37 +0900
	message:
	  start dpush test.

$ bzr dpush git+ssh://git@github.com/k-hashioka/bzr-branch.git,branch=master --remember

