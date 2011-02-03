The WebID Mercurial Repo
========================

  All Invited Experts should have access to it. This should be a good
  place to edit the spec before we push it to svn, to put test cases,
  and other code.
        
        $ hg clone https://dvcs.w3.org/hg/WebID
        $ cd WebID
	$ echo "[ui]" >>.hg/hgrc
	$ echo "username=${W3C_USERNAME}" >>.hg/hgrc
        
        # edit files
        
        $ hg add ${newfiles}
        $ hg commit
        $ hg push

        $ hg pull
        
  Use your W3C username and password.

