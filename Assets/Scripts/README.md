# Scripts
All our custom C# code is located in this folder.

Refer to the list bellow for a high level description of what each file does:

- **SceneUnderstandingHandler.cs**: The main controller that ties together scene understanding, photo wall generation and the user interface.
- **layout-generation/PhotoWallGenerator.cs**: Generates and displays photo walls for the detected walls.
- **layout-generation/algorithm.cs**: Defines the photo wall layout generation algorithms.
- **layout-generation/game_objects.cs**: Defines the classes to represent walls and photographs.
- **layout-generation/mymain.cs**: Defines a file reader that prefetches the image raw data from disk.
