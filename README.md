# Experiment: Keyboard Automation – Simulate Keys using UiPath Studio

## Aim
To simulate keyboard key presses using UiPath Studio for automating user input actions like typing text, using hotkeys, or navigating UI elements.

## Materials Required
- UiPath Studio
- Any application or website to test keyboard inputs (e.g., Notepad, browser)

## Procedure

1. **Create a New Project**  
   Open UiPath Studio and create a new Process project named `KeyboardAutomation`.

2. **Open Main.xaml**  
   Ensure the `Main.xaml` file is open in the workflow designer.

3. **Launch a Target Application**  
   - Use **Start Process** to open Notepad:
     ```plaintext
     File Name: notepad.exe
     ```

4. **Use Type Into Activity**
   - Drag a **Type Into** activity and attach it to the Notepad window.
   - Enter some text (e.g., "Hello, this is a keyboard automation test").
   - In the **Properties** panel, enable the **SimulateType** checkbox to simulate actual keyboard input.

5. **Simulate Hotkeys**
   - Use **Send Hotkey** activity to perform keyboard shortcuts.
   - Example: Use `Ctrl + S` to trigger the Save command in Notepad.

6. **Add Additional Key Actions**
   - Use **Send Hotkey** again for other combinations like `Ctrl + A`, `Ctrl + C`, `Ctrl + V`, etc.

7. **Run the Workflow**
   - Execute the workflow to observe the automated typing and keyboard shortcuts.


## Output:

![Screenshot 2025-05-08 142248](https://github.com/user-attachments/assets/2c4f4bdc-0c4e-48dd-a8f2-a58d90022cf7)

![OUTPUT (2)](https://github.com/user-attachments/assets/e35317c8-77d7-49b2-a7d6-1ac7f6dfc935)


## Result
UiPath successfully simulates key presses such as typing text and triggering hotkeys within an application.
