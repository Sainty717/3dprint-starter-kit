# 3D Printing Starter Info Pack

## Introduction to 3D Printing
3D printing is a fascinating technology that allows you to create physical objects from digital designs. Whether you're a hobbyist, an artist, or an engineer, 3D printing can bring your ideas to life.

## Essential Software for 3D Printing

### Fusion 360
- **Purpose**: Model design
- **Description**: Fusion 360 is a powerful CAD (Computer-Aided Design) software that allows you to create intricate 3D models. It's user-friendly and ideal for both beginners and experienced designers.
- **Download**: [Fusion 360](https://www.autodesk.com/products/fusion-360/overview)

### Prusa Slicer
- **Purpose**: Slicing software
- **Description**: Prusa Slicer is used to convert your 3D model into instructions that a 3D printer can understand. It slices your model into layers and generates the necessary code for printing.
- **Download**: [Prusa Slicer](https://www.prusa3d.com/prusaslicer/)

## Resources for 3D Printing

### Thingiverse
- **Description**: A vast repository of free 3D models that you can download and print.
- **Link**: [Thingiverse](https://www.thingiverse.com/)

### Printables
- **Description**: Another great source for free 3D models, focusing on practical and fun prints.
- **Link**: [Printables](https://www.printables.com/)

### CNC Kitchen
- **Description**: A YouTube channel dedicated to 3D printing, offering tutorials, reviews, and tips.
- **Link**: [CNC Kitchen YouTube](https://www.youtube.com/@CNCKitchen)

### Makers Muse
- **Description**: A YouTube channel that explores the possibilities of 3D printing and provides educational content on design and printing techniques.
- **Link**: [Makers Muse YouTube](https://www.youtube.com/@MakersMuse)

### All3DP
- **Description**: A comprehensive resource for print temperatures and settings, as well as news, reviews, and guides on 3D printing.
- **Link**: [All3DP](https://all3dp.com/)

## Checklist for Printing

1. **Level the Bed (Auto Bed Leveling)**
   - Ensure your printer’s auto bed leveling function is properly calibrated. If you change the plastic (filament), adjust the temperature of the bed accordingly for proper leveling.

2. **Clean the Bed**
   - Ensure the bed is free from any debris or previous print residue.

3. **Apply Glue to the Bed**
   - Apply a thin layer of glue to help the print adhere better to the bed.

4. **Move to SD Card**
   - Transfer the sliced file from your computer to the SD card that your 3D printer uses.

5. **Print from Media**
   - Insert the SD card into the 3D printer and start printing.

## Importing PrusaSlicer Configuration

To ensure you have the optimal settings for your prints, you can import the provided PrusaSlicer configuration bundle.

### Steps to Import PrusaSlicer Configuration Bundle

1. **Download the Configuration File**
   - Download the `PrusaSlicer_config_bundle.ini` file from the GitHub repository.

2. **Open PrusaSlicer**
   - Launch the PrusaSlicer application on your computer.

3. **Go to Configuration Menu**
   - In PrusaSlicer, navigate to the `File` menu.

4. **Import Configuration**
   - Select `Import` from the dropdown menu, then choose `Import Config Bundle...`.

5. **Select the Configuration File**
   - Locate the `PrusaSlicer_config_bundle.ini` file you downloaded and select it.

6. **Confirm Import**
   - PrusaSlicer will import the settings. You may need to restart the application for changes to take effect.

## Good to Knows

### Manual Bed Leveling
- **Description**: Manual bed leveling involves adjusting the screws at the bottom of the bed to start with a level surface. This reduces the work the probe has to do to compensate during printing.
- **Tip**: Begin by adjusting all screws to a similar tightness and then fine-tune each corner until the bed is level.

### PID Tuning
- **Description**: PID (Proportional-Integral-Derivative) tuning helps maintain a consistent temperature for your 3D printer’s hotend and heated bed.
- **Tip**: Regular PID tuning can improve print quality by reducing temperature fluctuations. This can be done through your printer’s firmware settings or control panel.

### Steps Tuning
- **Description**: Steps tuning involves calibrating the steps per millimeter for your printer’s axes to ensure accurate movements.
- **Tip**: Although usually not needed, it’s good to know how to perform steps tuning if you notice dimensional inaccuracies in your prints. Check your printer's manual for instructions.

### Offsets
- **Description**: Offsets refer to the adjustments made to account for the distance between the print bed and the nozzle when the printer is at its home position.
- **Tip**: Properly setting your Z-offset is crucial for the first layer adhesion. Make small adjustments as needed to achieve the perfect first layer.

By following this guide, you’ll be well on your way to creating amazing 3D prints. Happy printing!
