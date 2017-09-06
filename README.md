# Unreal Multiplayer Course - Section 2 - Menu System

How to create rich UI using Unreal's UMG in C++. This project lays the foundations for creating complex menu systems for multiplayer games. 

### 1 Create a Menu Blueprint ###

+ Importing last section's project.
+ Creating a menu Blueprint.
+ Revision of layout.
+ Create a basic menu.

### 2 Accessing UI Classes in C++ ###

+ Using the `FClassFinder`.
+ Finding `BP_PlatfromTrigger`.
+ Accessing UMG from C++.
+ Saving our menu class.

### 3 Load And Display UMG In C++ ###

+ Creating an interface.
+ `CreateWidget` in C++.
+ Setup a MainMenu level.

### 4 Changing UI Input Modes ###

+ Using `SetInputMode()`.
+ Configuring an input mode.
+ Displaying the cursor.
+ Repeat for yourselves.

### 5 Advanced UMG Widget Layout ###

+ How container widgets work.
+ Canvas panel.
+ Horizontal/vertical boxes.
+ Size boxes as spacers.
+ Overlay. 
+ Create a layout.

### 6 Custom Buttons And Fonts ###

+ 9-slice images for buttons.
+ Box vs border vs image.
+ Using Google fonts.
+ Scale box for backgrounds.
+ Make it pretty.

### 7 Solution: Custom Buttons And Fonts ###

+ We make our menu pretty.

### 8 Connecting UMG to C++ ###

+ Create a `UUserWidget` class.
+ Reparent the widget BP.
+ Add a bind widget property.
+ What do the errors mean?

### 9 Initialisers and UButton Callbacks ###

+ How to `Initialize` a UserWidget.
+ The UButton OnClick handler.
+ Add a dynamic handler.

### 10 Interfaces To Invert Dependencies ###

+ Intro to inverting dependencies.
+ How to make a interface in Unreal.
+ Using an interface for callbacks.
+ Injecting the dependency.

### 11 Solution: Injecting Dependencies ###

+ We solve last lecture's challenge.

### 12 Deactivating Menus ###

+ Refactoring our menu setup.
+ Creating a teardown stub.
+ Reversing the setup logic.

### 13 Sub-Menus With Widget Switchers ###

+ What are widget switchers.
+ Creating a "Join" menu.
+ Styling the menu.

### 14 Solution: Styling Our Sub-Menu ###

+ We finish styling out menu.

### 15 Navigating Menus In C++ ###

+ Binding the WidgetSwitcher.
+ Investigating the API.
+ Switching menus.
+ Implement a back button.

### 16 Reading Text Fields From C++ ###

+ Set startup level.
+ Bind the text field.
+ Call the `Join()` function.
