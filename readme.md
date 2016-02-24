## Standard structure for a new experiment/paper.

        +---analysis                # All of the code to do the analysis should go here
        |   GenerateAllPlots.ipynb  # This file should generate *every* plot in the paper.
        |   +---final_plots         # Plots *included in the paper*    
        |   +---plots               # The output plots
        |   \---plots_edited        # Any plots that have been manually edited
        +---code                    # The experimental software
        +---datasets                # The datasets for this experiment
        |   \---deposit_ready       # A version of the data ready for deposit in the University service
        |       \---.ipynb_checkpoints
        +---ethics                  # The ethics application (template forms are provided)
        +---logs                    # Raw log files (i.e. not processed into datasets yet)
        +---paper                   # The paper source files (e.g. LaTeX source)
        |   +---enlighten_version   # The version that was submitted to Enlighten
        |   +---final               # The final camera ready version
        |   +---imgs                # Any images to be included
        |   +---output              
        |   \---thumbnail           # A thumbnail image of the paper
        +---poster                  # The poster files
        |   \---imgs                # Images used on the poster    
        |   \---logos               # University logos
        +---talk                    # The talk powerpoint files
        |   +---imgs                # The images for the talk
        |   \---videos              # The videos for the talk
        \---video                   # Video data
            +---assets              # Assets (e.g. 3D models, slides etc.)
            +---audio               # Voiceovers, music
            +---final               # The final submitted video
            \---raw_footage         # Raw footage files
