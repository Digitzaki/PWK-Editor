# PWK-Editor

Version: 1.2

Developed by: Akira Ryuzaki (Digitzaki)

# Description:
Pipeworks Editor is a versatile application designed to assist you in color visualization, gradient creation, and mip map generation. It provides a user-friendly interface to simplify these tasks. Here's a brief overview of its key features:

# Feature 1: Color Visualizer

- Color Visualizer helps you fine-tune and visualize colors using Red, Green, Blue, and Alpha channels.
- Three sliders for Red, Green, and Blue allow precise control with values rounded to the second decimal.
- LP=KA? corresponds to Red, LO=KA? corresponds to Green, and LQ=KA? corresponds to Blue, making it easy to understand and edit.
- The Alpha slider (LR=KA?) ranges from 1 to 5, adjusting the transparency of the color.
- As the color values approach 0, the color becomes more transparent.

# Feature 2: Gradient Visualizer

- The Gradient Visualizer assists in creating color gradients with ease.
- A slider controls the number of different colors, grouping them into RGB segments.
- Colors within each segment are evenly distributed, simulating smooth transitions.
- The output is in the format LP=KE? for Red, LO=KE? for Green, and LQ=KE? for Blue, without simulating transparency (LR=KA?).
- Modular output transforms =KE? into =KA? when there is only one value. Will also combine repeated values at the end to save space, while keeping the desired output.

# Feature 3: Improved Mip Map Generator

- The Mip Map Generator streamlines the process of creating mip maps for your textures.
- Select input and output folders conveniently using the application's window.
- Input values from 1 to 6 in the text box to determine the mip map levels (each 50% smaller than the previous).
- Pipeworks Editor automatically generates a "mips" folder, categorizing and sorting based on the file location.
- If subfolders are present in your input location, the generator will organize in the same structure as the subfolders.

Pipeworks Editor simplifies the tasks of color manipulation, gradient creation, and mip map generation, making it a valuable tool for your design and development needs. Explore its features and enjoy a more efficient workflow.
