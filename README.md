# Some Basics

### Publish a webpage on *GitHub Pages*	
 To publish a webpage on github pages we can simply name the repositry on this syntax __username.repoName.io__ or we can just go to the settings page and there is an option for publish our webpage on github pages. 

### Git Basics:
 To completely remove a tracked folder or file from being tracked again.
 ![](inc/gitBasics.PNG)

 * When we have large files bigger than 100 mb which could not be uploaded via git we do: 
 > git filter-branch --index-filter 'git rm --cached --ignore-unmatch bigfile_name'