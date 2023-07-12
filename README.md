# ie-hugo-theme

some files refer document root such as /files. put these files in ie-web/ie directory.

    singularity exec /mnt/ie-virsh/singularity/hugo/hugo.sif hugo 

Then 
     rsync -av public/* destination

It will override exisiting files, so do it carefully.

