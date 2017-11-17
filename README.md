# ataraxia-website

## Instructions for uploading website to AFS

-Change directory to ataraxia-website so that when you run `ls` it shows `ataraxia` and `README.md`
-run `sftp [SUNET ID]@cardinal.stanford.edu`
- - e.g. `sftp aaga@cardinal.stanford.edu`
-if it gives a warning type `yes` and enter
-type your password and press enter
-select one of the options for two-step
-now if you run `ls` you should see a bunch of folders (these are your personal AFS folders)
-run `cd ../../../../../../afs/ir/class/cs147/WWW/projects/education`
-now if you run `ls` you should see all of the education section project names including `ataraxia`
-run `put -r ataraxia`
-this will replace the existing ataraxia folder with the new ataraxia folder that is in the ataraxia-website folder on your computer
-after it finishes uploading, the new website should be visible at
	http://web.stanford.edu/class/cs147/projects/education/ataraxia