# HelloYourName C# WPF Application

# Steps:
1. I started a new project: Visual C# --> Windows --> WPF Application --> HelloYourName
2. Opened Toolbox and expanded Common WPF Controls
3. Dragged TextBlock from Toolbox onto the Design View window
4. Repositioned the TextBlock to the upper left hand corner of the window
5. Opened the Properties Window from View menu
6. Changed the Properties --> Text --> Font Size to 20 px
7. Again, change the Font Size, this time in XAML, to 24 px
8. In Properties, changed the standard “TextBlock” text to “Please enter your name”
9. After seeing the length of the new text, I repositioned the text block
10. Added a TextBox directly below the TextBlock.
11. Resized TextBox to align with both edges of the TextBlock
12. Renamed TextBox to “userName”
13. From Toolbox, added a Button, horizontally aligned and to the right of the TextBox
14. Changed the Name property of Button to “ok” and the text content to “OK”
15. Changed the Title of the Design View Window to “TayHello”
16. Adjusted the size of the Design View Window to be nearly equal all around.
17. “Build Solution” was started and verified the project built successfully.
18. After debugging, I verified the Window View looked identical to the textbook
19. Opened Event Handlers for the button
    - Typed okClick in the “Click” section
    - This navigated me to the MainWindow.xaml.cs file, where I typed “MessageBox.Show(“Hello “ + username.text);” in the okClick function
20. Finished up project with building and debugging and provided the final results as a
screenshot.

# Reflection:
Using this part of Visual Studio was new for me, I have never used their graphical interface
before. Everything learned here was new. I am glad the textbook was so thorough because
there is a lot to Visual Studio. I mistakenly placed a TextBox where there should have been a
TextBlock, but Sharp [textbook author] quickly warned against that so I was able to catch the error in time. The
major lesson learned here was how to build a Window application using this new interface. It
was pretty easy once you get the hang of it. I like the way they handle the code, as it makes it
pretty simple. You just click on the properties and event handler of the button or other item
you want to code, and that automatically generates the function you need, where you type the
code. I think this is the most complicated it got for this assignment, as everything else was just
clicking and dragging items to the Window, arranging them appropriately, and adjusting values
in Properties.