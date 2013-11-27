keepcomment.vim
===============
simple comment out plugin

      `u    comment line(s)
      `o    uncomment line(s)

      `i    comment line(s) while keep coding
            for trying new code line
            but if you want code line(s) keep intact
            ( default : same as `k, that is, to the upper )

      `k    comment out to the upper
      `j    comment out to the below
      
Visual blocking or numbering(buffer count) in normal mode
will work as expected.

Currently
for
        python, Makefile, snippet, cpp, javascript, ruby, sh
        matlab, tex, txt, anonymous, c, html

You might feel free to add other comment string and filetype
by modifying s:CommentStringMap
and sure you can change key map to your favorite.

