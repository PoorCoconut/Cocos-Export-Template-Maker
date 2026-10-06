# Coco's Custom Export Template Maker (Godot Engine)

*Fork this repository to effectively use it.*

1. This works by getting a main input `custom.py`. This is a sort of config file to define specific compiler options.
You may visit this wonderful website https://godot-build-options-generator.github.io/ to create YOUR custom builds easily!
2. Commit this new custom.py in your repository.
3. Proceed to the ***Actions Tab*** and click on the *'Build Custom Export Templates'* job
4. Run the workflow and configure your version and whether or not you want to export on web or on windows.
5. Once finished, you are able to see the Custom Export Template in your __Job's Summary__. Scroll down to the Artifacts part.
6. Unzip the contents and store it somewhere safe. (You will find 2 `.exe`s)
7. In Godot, go to ***Project > Export***. You may configure what export you're using Web / Windows Desktop if you didn't change the workflow. 
To your right, you will see ***Custom Template***, in release (assuming you are releasing the game), put the file path of the desired `.exe` in and Export!

Right now, this requires a bit more testing. I've found that my Godot games had a MASSIVE ***58% file size reduction*** using the current `custom.py` in this repository.
*Note: The current `custom.py` is made for exporting 2D games with low file sizes. It typically ran for only around 17 minutes.*


