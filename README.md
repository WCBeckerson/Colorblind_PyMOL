# Colorblind palette for PyMOL
#The code for adapting models to a colorblind-friendly palette 

      ##The following code, adapted from code produced by KP @MolecularMemory on YouTube, can be plugged into the PyMOL terminal to create a colorblind-friendly model using the palette recommended by Bang Wong (2011) (https://doi.org/10.1038/nmeth.1618).

  bg_color white
  set antialias=1
  set orthoscopic=1
  set gamma=1.15
  set cartoon_fancy_helices, 1
  set cartoon_fancy_sheets, 1
  set_color WongBlack, [0,0,0]
  set_color WongOrange, [230,159,0]
  set_color WongSkyBlue, [86,180,233]
  set_color WongBluishGreen, [0,158,115]
  set_color WongYellow, [240,228,66]
  set_color WongBlue, [0,114,178]
  set_color WongVermillion, [213,94,0]
  set_color WongReddishPurple, [204,121,167]
  set ray_shadows, 0
  set ray_trance_fog, 1

        ##To show the PAE scores on you model, you can use these colors with the 'spectrum b' command:

  spectrum b, WongOrange WongSkyBlue

        ##Right (r), Left (l), and Middle (m) circle colors
      r_col_upreg = "#7FD7F7"		Top “upregulated” region of the right circle
      r_col_downreg = "#528AA1"	Bottom “downregulated” region of the right circle

      l_col_upreg = "#FBEF49"		Top “upregulated” region of the left circle
      l_col_downreg = "#EAA407"	Bottom “downregulated” region of the left circle

      m_col_upreg = "#9353AF"	Top “upregulated” regions of the center circle
      m_col_downreg = "#501b6b"	Bottom “downregulated” region of the center circle
