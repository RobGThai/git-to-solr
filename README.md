git-to-solr
===========

Index git history into a Solr repository. Represents commit's content (file changed, etc) as nested documents. Tested against Solr 4.9 .

Inspired by [Gary Sieling's solr-git](https://github.com/garysieling/solr-git) and [JGit-Cookbook](https://github.com/centic9/jgit-cookbook).

Start Solr server by running **java -Dsolr.solr.home=\<project-root\>/solr -jar start.jar** from Solr distribution's example directory.
