# Open Source Keyboard Notes

The goal of this markup is to display the notes gathered around Open Source Keyboards.


# QMK

QMK (Quantum Mechanical Keyboard) is an open-source firmware project that allows you to program and customize the behavior of mechanical keyboards. It provides a flexible and powerful platform for creating custom keyboard layouts, macros, and advanced features.

QMK firmware supports a wide range of keyboards, including popular keyboard brands and DIY keyboard projects. It is designed to be highly configurable and adaptable to various keyboard layouts and key matrix configurations.

Key features and capabilities of QMK include:

1. Custom Keymaps: QMK allows you to define and customize keymaps, which determine the function of each key on your keyboard. You can create multiple layers of keymaps, enabling different functions or macros for each layer. This flexibility allows you to design a keyboard layout tailored to your specific needs.

2. Advanced Macros: QMK supports the creation of complex macros, allowing you to automate sequences of keystrokes or perform custom actions. Macros can be assigned to specific keys or triggered by key combinations, providing additional functionality and productivity enhancements.

3. Tap Dance: The Tap Dance feature in QMK allows you to assign different actions to keys based on the number of times they are tapped. For example, a single tap could produce one character, while a double tap could produce a different character or execute a specific function.

4. RGB Lighting Control: QMK provides capabilities for controlling RGB lighting on keyboards that support it. You can define lighting effects, colors, and animations, adding a visually appealing element to your keyboard.

5. Firmware Customization: QMK allows you to modify and customize various firmware settings, such as debounce time, key repeat rates, and other low-level keyboard behavior. This level of customization ensures a responsive and personalized typing experience.

6. Community and Collaboration: QMK has a vibrant and active community of keyboard enthusiasts and developers. The community contributes to the project by sharing keyboard configurations, offering support, and continuously improving the firmware.

QMK is widely used by keyboard enthusiasts, mechanical keyboard manufacturers, and DIY keyboard builders. It provides a powerful platform for creating and customizing unique keyboard experiences, making it a popular choice for those seeking a highly customizable and programmable mechanical keyboard.



# ZMK

ZMK (Zephyr Mechanical Keyboard) is an open-source firmware project specifically developed for mechanical keyboards. It is built on top of the Zephyr Project, an open-source real-time operating system (RTOS) designed for resource-constrained devices.

ZMK aims to provide a flexible and modular firmware platform for creating custom mechanical keyboards. It offers features and capabilities similar to QMK, but with a focus on leveraging the Zephyr RTOS and taking advantage of its scalability, security, and compatibility with a wide range of microcontrollers.

Key aspects and features of ZMK include:

1. Zephyr Integration: ZMK is built on the Zephyr Project, which provides a robust and scalable RTOS foundation. This integration enables ZMK to leverage the features and benefits offered by the Zephyr ecosystem, such as device support, hardware abstraction layers, and real-time capabilities.

2. Modularity and Customization: ZMK follows a modular architecture, allowing you to select and configure specific components to build your firmware. It provides a set of reusable modules for key scanning, Bluetooth connectivity, OLED displays, and other common keyboard functionalities. This modularity allows for greater customization and adaptability.

3. Wireless Connectivity: ZMK includes support for wireless connectivity protocols, such as Bluetooth. This enables the creation of wireless mechanical keyboards, providing flexibility and convenience in keyboard usage.

4. Configuration via Device Tree: ZMK utilizes the Device Tree mechanism, which is a data structure used to describe hardware properties and configurations. Device Tree allows for easy configuration and customization of keyboard features without modifying the firmware source code.

5. ZMK Configurator: ZMK provides a web-based configurator tool that simplifies the process of creating and customizing keyboard layouts, keymaps, and other settings. The configurator offers an intuitive interface for designing your keyboard's behavior and generating the necessary firmware files.

6. Community and Collaboration: Similar to QMK, ZMK has an active and growing community of keyboard enthusiasts and developers. The community contributes to the project by sharing configurations, providing support, and collaborating on firmware improvements and feature additions.

ZMK is gaining popularity as an alternative firmware option for mechanical keyboards, particularly for those interested in leveraging the capabilities of the Zephyr RTOS. It offers a flexible and extensible platform for creating custom keyboards with support for various features and wireless connectivity options.

# Types of Mechanical Keyboards

There are several different types of mechanical keyboards, each distinguished by the type of mechanical key switches they use. The key switches determine the tactile feedback, actuation force, and sound produced by the keys. Here are some common types of mechanical key switches:

1. Cherry MX: Cherry MX is one of the most popular and widely recognized mechanical key switch brands. It offers a variety of switches, including:

   - Cherry MX Red: Linear switch with a light actuation force and smooth keystrokes.
   - Cherry MX Brown: Tactile switch with a light actuation force and a slight bump for feedback.
   - Cherry MX Blue: Tactile and clicky switch with a higher actuation force and an audible click sound.
   - Cherry MX Black: Linear switch with a higher actuation force and a more pronounced keystroke.
   - Cherry MX Speed Silver: Linear switch with a shorter actuation distance for faster typing and gaming.

2. Gateron: Gateron is another well-known switch manufacturer that produces switches similar to Cherry MX switches. Gateron switches are often considered smoother and less costly compared to Cherry MX switches. They offer various options, including Gateron Red, Brown, Blue, Black, and more.

3. Kailh: Kailh is a switch manufacturer that produces a range of mechanical switches, including their own versions of popular switches. Kailh switches are known for their smooth keystrokes and competitive pricing. Kailh offers switches such as Kailh Red, Brown, Blue, Black, and more.

4. Topre: Topre switches are electro-capacitive switches that combine elements of mechanical and rubber dome keyboards. They provide a unique typing experience, with a tactile bump and a smooth keystroke. Topre switches are considered high-quality and are often found in premium keyboards.

5. Buckling Spring: Buckling spring switches are known for their distinctive tactile and audible feedback. They feature a coiled spring that buckles under pressure, producing a satisfying click sound and tactile response. Buckling spring switches are commonly associated with IBM Model M keyboards.

6. Alps: Alps switches were popular in vintage keyboards and are still used in some modern mechanical keyboards. They come in different variations, including Alps SKCM, Alps SKCL, and Alps SKBL. Alps switches provide a tactile or linear typing experience, depending on the specific type.

These are just a few examples of mechanical key switch types, and there are other brands and switch variations available in the market. The choice of mechanical key switch ultimately depends on personal preference, typing style, and desired typing experience.


# Tools Needed To Create A Mechanical Keyboard

Creating your own mechanical keyboard requires a few essential tools and components. Here's a list of the basic tools and materials you'll need:

1. Keyboard Kit or Components: You'll need a keyboard kit or the individual components to build your own keyboard. This typically includes a PCB (printed circuit board), a case, key switches, keycaps, stabilizers, and any additional features like LEDs or programmable controllers. You can purchase these components separately or opt for a pre-packaged keyboard kit that includes all the necessary parts.

2. Soldering Iron and Solder: Most mechanical keyboards require soldering to attach the switches to the PCB. You'll need a soldering iron, preferably with a fine tip, and solder wire to establish electrical connections. Make sure to choose a soldering iron with appropriate temperature control and safety features.

3. Desoldering Tools (optional): If you plan to modify or reuse switches, desoldering tools like a desoldering pump or desoldering wick may be necessary to remove existing solder connections.

4. Keycap Puller: A keycap puller is a small tool designed to safely and easily remove the keycaps from the keyboard. It helps prevent damage to the keycaps or the switches during the removal process.

5. Switch Opener (optional): If you want to lubricate or modify the switches, a switch opener tool can be handy. It helps safely open the switch housing for maintenance purposes.

6. Tweezers and Small Screwdrivers: Tweezers can be useful for handling small components and placing keycaps precisely. Small screwdrivers may be needed to secure the PCB, case, or other components.

7. Lubricant (optional): If you prefer a smoother keystroke, you may consider using a keyboard switch lubricant. Lubricants can reduce friction and noise in mechanical switches. There are various lubricant options available, such as lubricating greases or oils specifically designed for mechanical keyboards.

8. Diodes and Resistors (if necessary): Depending on the keyboard's design and features, you may need diodes and resistors for certain customizations or modifications. These components are typically included in the keyboard kit or specified in the build documentation.

9. Workspace and Lighting: Set up a clean and well-lit workspace with adequate ventilation. A comfortable and organized workspace will make the assembly process easier and safer.

10. Documentation and Resources: Gather the necessary documentation, build guides, and resources specific to your keyboard kit or components. These resources will provide step-by-step instructions and help troubleshoot any issues that may arise during the build process.

Remember to follow proper safety precautions when working with tools, soldering irons, and other equipment. If you're new to keyboard building, it can be helpful to refer to online communities, forums, and tutorials where experienced enthusiasts share their expertise and provide guidance throughout the process.


# What is a Macropad?

A macro pad, also known as a macro keypad or programmable keypad, is a small peripheral device that consists of a set of buttons or keys that can be programmed to execute customized commands or macros. It is typically used as an extension to a keyboard, providing additional programmable inputs for quick access to specific functions or actions.

Here are some key features and uses of macro pads:

1. Programmable Buttons: Macro pads offer programmable buttons or keys that can be assigned with specific commands, keystrokes, shortcuts, or macros. Each button can be customized to perform a specific action, such as launching applications, executing complex commands, inputting text, or triggering multimedia functions.

2. Customization and Productivity: Macro pads allow users to create personalized shortcuts and streamline repetitive tasks. By assigning frequently used commands or macros to dedicated buttons, users can save time and boost productivity. They are particularly useful for content creators, gamers, programmers, and professionals who rely on specific keyboard shortcuts or complex workflows.

3. Compact and Portable: Macro pads are often designed to be compact and portable, making them easy to carry and use alongside a laptop or a keyboard. They can serve as a space-saving alternative to a full-sized keyboard with programmable features.

4. Integration with Keyboard or Standalone: Macro pads can be used as standalone devices, connected to a computer or a device via USB, and programmed independently. They can also be integrated with a keyboard, either as an extension or an add-on module. Some keyboards have modular designs that allow attaching or detaching macro pads as needed.

5. RGB Lighting and Customization: Many macro pads feature RGB lighting options, allowing users to customize the color, brightness, and effects of the backlighting. This can provide aesthetic appeal and visual cues for different macros or functions.

6. Gaming Applications: Macro pads are popular among gamers as they provide additional programmable inputs for gaming macros, hotkeys, or complex command sequences. Gamers can assign macros for in-game actions, weapon switching, building structures, or executing complex combos with a single button press.

7. Stream Deck: A specific type of macro pad that gained popularity among content creators and streamers is the Elgato Stream Deck. It features an array of customizable LCD buttons that can display icons or images, making it easy to visually identify different macros or actions.

Macro pads can be purchased as standalone devices from various manufacturers, or they may be integrated into certain keyboards or gaming peripherals. They often come with dedicated software or configuration utilities that allow users to program and customize the button assignments and settings.

Overall, macro pads provide a convenient and customizable solution for users who need quick access to a set of programmable inputs, helping to optimize workflows, enhance productivity, and streamline repetitive tasks.

# What are Macros?

In computing, a macro refers to a series of predefined instructions or commands that can be executed as a single command or action. It allows for the automation or simplification of repetitive or complex tasks by condensing multiple steps into a single command.

Here are some key points about macros:

1. Automation: Macros are often used to automate repetitive tasks that involve a sequence of actions. Instead of manually performing each step, a macro can be created to execute the entire sequence with a single command or keystroke.

2. Time-Saver: Macros save time by eliminating the need for manual repetition of tasks. They can be particularly useful for tasks like formatting documents, performing calculations, data entry, generating reports, or manipulating large sets of data.

3. Recorded Actions: Many macro systems allow users to record their actions as they perform a task. The macro recorder captures the series of mouse clicks, keystrokes, and other interactions, and converts them into a macro. The recorded macro can then be played back to repeat the same set of actions.

4. Scripting or Programming: In some cases, macros are created by writing scripts or programming code. This allows for more advanced functionality and customization. Programming languages like Visual Basic for Applications (VBA) or scripting languages like AutoHotkey are commonly used for creating macros.

5. Application-Specific: Macros are often specific to a particular software application or environment. Different applications, such as word processors, spreadsheets, image editors, or programming IDEs, may provide their own macro systems or scripting capabilities for automation and customization.

6. Customization: Macros can be customized to suit individual needs and preferences. Users can define the specific actions, parameters, and conditions within a macro. This flexibility allows for the creation of tailored solutions for specific tasks or workflows.

7. Keyboard Shortcuts: Macros are frequently assigned to keyboard shortcuts, allowing users to trigger them quickly and easily. By pressing a specific key combination or assigning a function key, the associated macro is executed.

Macros are widely used in various domains, including office productivity, data analysis, software development, and gaming. They provide a way to streamline tasks, reduce errors, and improve efficiency by automating repetitive or complex operations.

It's important to note that while macros can be powerful tools, they should be used judiciously and with caution. Care should be taken to ensure that macros are properly tested, secure, and do not compromise the integrity or security of the system or data.


# How to create Macros?

Creating macros typically involves the following steps, although the specifics may vary depending on the software or application you're working with:

1. Determine the Task: Identify the repetitive or complex task that you want to automate with a macro. This could be a series of actions, keystrokes, or commands that you perform regularly.

2. Choose the Macro System: Determine the macro system or tools available within the software or application you're using. Many applications provide built-in macro functionality, while others may require the use of external scripting or automation tools.

3. Recording the Macro (If Applicable): If the macro system supports recording, you can record your actions as you perform the desired task. This captures the sequence of steps and translates them into a macro. To record a macro, typically you would initiate the recording, perform the actions, and then stop the recording.

4. Edit or Customize the Macro: Once the macro is recorded or created, you may need to edit or customize it to suit your specific needs. This could involve modifying parameters, adding conditions, or incorporating additional commands.

5. Assign a Trigger: Determine how you want to trigger the macro. This can be done by assigning a keyboard shortcut, associating it with a specific button or menu item, or linking it to an event or condition.

6. Test and Refine: Test the macro to ensure it performs the desired actions correctly. Make any necessary adjustments or refinements to the macro logic or settings.

7. Save the Macro: Save the macro in a location where it can be accessed when needed. Some macro systems allow you to organize macros into groups or categories for easier management.

8. Documentation: It's helpful to document your macros, especially if you have multiple macros or if you plan to share them with others. Documenting the purpose, trigger, and steps involved in each macro can be useful for future reference or troubleshooting.

It's worth noting that the exact steps and options for creating macros vary across different software applications and macro systems. Some applications may require scripting or programming knowledge to create more advanced macros. Additionally, there are dedicated macro or automation tools available that provide extensive features and flexibility for creating macros across multiple applications.

It's recommended to consult the documentation or help resources specific to the software or macro system you are using for detailed instructions and guidance on creating macros.

# What Python libraries are used to create Macros?

In Python, there are several libraries and modules that can be used to create macros or automate tasks in specific applications or environments. Here are a few commonly used libraries for macro creation in Python:

1. pyautogui: pyautogui is a cross-platform library that allows you to programmatically control the mouse and keyboard. It provides functions for automating mouse movements, clicks, keyboard input, and screen interactions. pyautogui is often used to create macros for automating repetitive tasks or simulating user input.

2. keyboard: The keyboard library provides functions for capturing and controlling keyboard events. It allows you to listen for keypresses, simulate keypresses, and perform actions based on specific key combinations. This library is useful for creating macros that respond to keyboard input or perform actions triggered by specific keys.

3. pywinauto: pywinauto is a library specifically designed for automating Windows applications. It allows you to interact with GUI elements, automate window management, and simulate user actions. pywinauto is commonly used for creating macros that interact with and control Windows applications.

4. Selenium: Selenium is a popular library for automating web browsers. It provides a range of functions for interacting with web elements, submitting forms, navigating web pages, and extracting data from websites. Selenium is often used for creating macros that automate web interactions or perform web scraping tasks.

5. pygetwindow: pygetwindow is a library that allows you to manipulate and interact with windows on your desktop. It provides functions for finding windows, moving and resizing windows, and retrieving window properties. pygetwindow can be useful for creating macros that automate window management or interact with specific application windows.

6. pyperclip: pyperclip is a simple library that provides functions for accessing the clipboard. It allows you to read from and write to the clipboard, making it useful for macros that involve copying and pasting text or data.

These are just a few examples of libraries that can be used for creating macros in Python. The choice of library depends on the specific requirements of your macro and the application or environment you are working with.

Keep in mind that the availability and suitability of these libraries may vary depending on the task and the software you are trying to automate. It's recommended to refer to the documentation and resources specific to each library for more information on their usage and capabilities.

# What are Keycaps?

Keycaps are removable covers or caps that are placed on top of the switches of a keyboard. They are the visible and tactile parts of the keyboard that users interact with when typing. Keycaps are designed to provide a comfortable and functional surface for pressing down on the switches, allowing users to input characters, commands, or functions.

Keycaps come in a variety of shapes, sizes, and designs to fit different types of switches and keyboard layouts. They typically have legends (characters, symbols, or markings) printed or engraved on their top surface, indicating the function or character associated with each key.

Keycaps serve several purposes:

1. Ergonomics: Keycaps are designed to provide a comfortable and ergonomic typing experience. They have profiles that determine the shape and contour of the keycap, which can affect hand positioning and reduce strain during long typing sessions.

2. Customization: Keycaps offer a way to personalize and customize the appearance of a keyboard. They come in various colors, styles, and materials, allowing users to create a unique and visually appealing keyboard setup.

3. Visibility and Legibility: The legends on keycaps ensure that users can easily identify and locate the desired keys. The legends are typically printed or engraved using high-contrast colors or techniques to enhance visibility and legibility.

4. Durability and Protection: Keycaps provide protection for the switches underneath by acting as a barrier against dust, debris, and liquid spills. They also help prevent the switches from wearing down over time, as the keycaps themselves can be replaced if they become worn or damaged.

Keycaps can be easily removed and replaced, allowing users to switch between different keycap sets or customize individual keys to suit their preferences or specific needs. This flexibility makes keycaps a popular choice for keyboard enthusiasts, gamers, and those seeking a personalized typing experience.


# What are the Parts that makes a keycap?

A keycap consists of several components that work together to form a complete keycap assembly. Here are the main parts that make up a keycap:

1. Keycap Body: The keycap body is the main part of the keycap that covers the switch on the keyboard. It is the visible portion of the keycap that users interact with. The keycap body determines the shape, size, and overall design of the keycap.

2. Stem: The stem is the underside of the keycap that connects and aligns with the switch stem. It can vary in shape and size depending on the keyboard switch type (e.g., Cherry MX, Alps, etc.). The stem ensures proper alignment and stability when the keycap is attached to the switch.

3. Legends: Legends are the characters, symbols, or markings displayed on the top surface of the keycap. They indicate the function or character associated with that key. Legends can be printed, etched, engraved, or created using various methods like double-shot molding or dye-sublimation.

4. Keycap Profile: The profile refers to the shape and contour of the keycap. Different keycap profiles, such as OEM, Cherry, SA, DSA, or XDA, have distinct designs and heights. The profile affects the overall typing experience and the ergonomics of the keyboard.

5. Stabilizer Inserts: Some keycaps, particularly larger keys like the spacebar or enter key, require stabilizers to ensure smooth and even key movement. Stabilizer inserts fit into the keycap body and interact with the stabilizer mechanism on the keyboard to provide stability and reduce wobbling.

6. Keycap Locking Mechanisms: Keycaps may incorporate locking mechanisms to securely attach them to the switch. Common locking mechanisms include Cherry MX-style cross stems, Alps-style Alps switches, or Topre-style Topre switches. These mechanisms ensure that the keycap remains in place during use.

7. Materials and Surface Finish: Keycaps can be made from various materials, such as ABS (Acrylonitrile Butadiene Styrene), PBT (Polybutylene Terephthalate), POM (Polyoxymethylene), or specialty materials like metal or wood. The surface finish of keycaps can range from smooth and glossy to textured or matte, depending on the desired look and feel.

Each of these parts plays a role in the functionality, aesthetics, and overall user experience of the keycap. Manufacturers may vary in their specific design choices and materials used, resulting in a wide range of keycap options available in the market.

# What software is used to design keycaps?

Yes, there are software tools that facilitate the design and customization of keycaps. These tools enable users to create and visualize keycap designs, customize legends, and even generate 3D models for manufacturing. Here are a few examples of software commonly used for keycap design:

1. Adobe Illustrator: Adobe Illustrator is a popular vector graphics editor that many designers use for creating keycap designs. It provides a wide range of design tools, including shape creation, text manipulation, and color customization. Illustrator allows for precise control over keycap design elements and is suitable for creating intricate and detailed designs.

2. Inkscape: Inkscape is a free and open-source vector graphics editor similar to Adobe Illustrator. It offers a range of features for creating keycap designs, such as shape creation, path editing, and text manipulation. Inkscape is a suitable option for those who prefer a free software alternative.

3. Keyboard Layout Editor (KLE): Keyboard Layout Editor is a web-based tool specifically designed for creating and visualizing keyboard layouts, including keycaps. It provides an intuitive interface where users can design and customize keycap layouts, assign legends, and choose key sizes and profiles. KLE allows you to export your design as an image or a text file for further processing. ( free )

4. Blender: Blender is a powerful 3D modeling software that can be used to create keycap designs in three dimensions. It offers a wide range of tools and features for designing complex shapes, textures, and surface details. Blender is suitable for users who want to create highly detailed and realistic keycap models for 3D printing or manufacturing.
( downloaded 3D model of a keycap ) 


# What is Cherry MX?

Cherry MX is a brand of mechanical keyboard switches manufactured by a German company called ZF Friedrichshafen AG. These switches are widely recognized and highly regarded in the mechanical keyboard community for their quality, durability, and tactile feedback.

Cherry MX switches are designed to replace traditional rubber dome switches commonly found in membrane keyboards. They are known for their mechanical construction, which consists of a spring-loaded stem that moves up and down within a metal housing. When a key is pressed, the stem compresses the spring, completing an electrical circuit and registering a keystroke.

One of the key features of Cherry MX switches is their tactile feedback and distinct actuation points. The switches offer different variations, each denoted by a different color, representing variations in the switch's behavior. The most common Cherry MX switch types are:

1. Cherry MX Red: Linear switch with a light touch, no tactile bump, and smooth keystrokes.
2. Cherry MX Brown: Tactile switch with a slight bump, providing feedback without being too pronounced.
3. Cherry MX Blue: Tactile and clicky switch with a noticeable tactile bump and an audible click sound.
4. Cherry MX Black: Linear switch similar to Cherry MX Red but with a heavier actuation force.
5. Cherry MX Clear: Tactile switch with a more pronounced bump and a higher actuation force compared to Cherry MX Brown.
6. Cherry MX Silent: Available in various colors, these switches feature built-in noise-dampening mechanisms to reduce the sound produced during key presses.

Cherry MX switches have become the industry standard for mechanical keyboards, and many keyboard manufacturers and enthusiasts use them in their designs. They offer a high level of reliability, precision, and customization options, making them popular among typists, gamers, and keyboard enthusiasts who appreciate the feel and performance of mechanical switches.


# What is included in the Keyboard kit?

Keyboard kits typically include a combination of the following components necessary to build a custom mechanical keyboard:

1. PCB (Printed Circuit Board): The PCB is a crucial component that serves as the foundation of the keyboard. It provides electrical connections for the switches, LEDs (if applicable), and other components. The PCB determines the layout, features, and firmware compatibility of the keyboard.

2. Case: The case is the enclosure that houses the PCB and other components, providing structural support and aesthetics. Keyboard cases come in various materials such as plastic, aluminum, or wood, and they can have different shapes, sizes, and designs.

3. Plate: The plate is a rigid metal or plastic sheet that sits between the PCB and switches. It helps stabilize the switches and provides uniform spacing between them. Plates come in different layouts (e.g., ANSI, ISO) and materials (e.g., aluminum, brass).

4. Switches: Mechanical switches are the key components that register keystrokes. Keyboard kits usually do not include switches by default, as the choice of switches is highly subjective and varies based on user preference. Switches are available in various types (e.g., Cherry MX, Gateron, Kailh) with different characteristics (e.g., linear, tactile, clicky) and actuation forces.

5. Keycaps: Keycaps are the visible and tactile interface between the user and the switches. They are the caps that cover the switches and have legends (symbols or characters) printed on them. Keyboard kits may or may not include keycaps, depending on the specific kit. Keycap materials can range from ABS plastic to PBT plastic to higher-end options like double-shot or dye-sublimated keycaps.

6. Stabilizers: Stabilizers are used for larger keys (e.g., spacebar, enter key) to ensure smooth and consistent keycap movement. They consist of a housing and wire mechanism that stabilize the keycap's movement when pressed. Some kits may include stabilizers, while others may require you to purchase them separately.

7. Mounting Hardware: Keyboard kits typically include various screws, standoffs, and spacers required to assemble the keyboard. These components secure the PCB, case, and plate together.

8. USB Cable: Many keyboard kits include a USB cable for connecting the keyboard to a computer. The cable may have different connector types (e.g., USB-A, USB-C) and come in various lengths and designs.

It's important to note that the specific components included in a keyboard kit can vary depending on the manufacturer, vendor, and the type of kit (e.g., DIY kit, hot-swappable kit). Some kits may include additional accessories like LEDs, diodes, or tools, while others may require you to source them separately. Always check the product listing or description to ensure you have a clear understanding of what is included in a particular keyboard kit.


# What is VIAL?
VIAL (VIA Configurator and Layout) is an open-source firmware configurator and keymap editor for mechanical keyboards. It is specifically designed to work with keyboards that support the VIA (Vial-Keyboard Integrated Advanced) firmware.

The VIA firmware is an open-source firmware that allows for easy customization and configuration of keyboard layouts, key assignments, macros, and other features. It is compatible with a wide range of popular keyboard PCBs (Printed Circuit Boards) and controllers.

VIAL serves as a graphical user interface (GUI) for configuring the VIA firmware. It provides a user-friendly interface where keyboard enthusiasts and users can visually customize their keyboard layouts, assign functions to keys, and configure various settings. VIAL eliminates the need for manual editing of firmware files, making the process of customizing and fine-tuning the keyboard layout more accessible to users.

The features and capabilities of VIAL may vary depending on the specific keyboard and firmware version being used. However, typical functions provided by VIAL include:

1. Keymap Editor: VIAL allows users to create or modify keymaps, assigning different functions or actions to each key on the keyboard. This includes assigning specific keycodes, creating macros, and defining layers for additional functionality.

2. Lighting Control: Many keyboards with VIA firmware support customizable backlighting or RGB lighting effects. VIAL provides options for configuring and customizing the lighting settings, such as colors, effects, and brightness levels.

3. Firmware Updates: VIAL often includes a feature for updating the keyboard firmware to the latest version. This ensures compatibility with new features, bug fixes, and improvements provided by the firmware developers.

VIAL is an open-source project, meaning its source code is publicly available and can be modified or contributed to by the community. This fosters collaboration, innovation, and the ability to tailor the firmware configuration experience to specific user preferences and requirements.

It's worth noting that VIAL is just one example of a firmware configurator and keymap editor. Other similar tools exist in the mechanical keyboard community, each tailored to specific firmware platforms or keyboard brands.

(https://get.vial.today/?ref=makerluis.com)


