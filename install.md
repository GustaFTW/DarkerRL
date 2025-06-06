# Installing Godot
> Just unzip the Godot_v4.4.1-stable_linux.x86_64.zip

# Configuring the project
> Double click on Godot_v4.4.1-stable_linux.x86_64, a project manager screen will pop-up, click on "Import" on the top left corner, go to the location of the project, then go on Godot Project and select the file project.godot (it'll have a white icon on the top left corner of the file), after that, if you selected the correct file, it'll appear a green message "Valid project found at path"

# Installing the python dependencies
> pip install -r requirements.txt 

# Step 1 - Run the game with classic Dark Souls controls
> Simply click on the play button on the top right corner to start the game

# Step 2 - Run the inference code before running the game
> python ./stable_baselines3_example.py \
--resume_model_path models/experiment_2 \
--inference \
--timesteps 100_000

## Step 2.1 - Wait for the code to wait connection on the port, it'll display the following message
> No game binary has been provided, please press PLAY in the Godot editor
>
> waiting for remote GODOT connection on port 11008

## Step 2.2 - Run the game
> Click the start button on the top right corner

# Step 3 - Answer the survey on google forms
> https://forms.gle/bEspaEp27TCvPnS39

