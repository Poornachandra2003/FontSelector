# FontSelector


The 'TextEditor' component is a simple React-based text editor that allows users to input text, select fonts, choose font weights, and toggle italic styling. It also provides options to save and reset the content, with feedback messages displayed upon saving or resetting.

## Features

- **Font Selection**: Choose a font family from a predefined list.
- **Font Weight & Style**: Adjust font weight and toggle italic styling.
- **Text Input**: Enter and edit text with the selected font settings.
- **Save/Reset**: Save the content to `localStorage` or reset it to default settings.
- **Feedback Messages**: Display messages when saving or resetting content.

## Installation

1. Clone the repository or download the project.
2. Navigate to the project directory.
3. Install the necessary dependencies:

   ```bash
   npm install

4. Ensure that you have the required font data in fontData.json and the necessary components (FontSelector and FontWeightSelector) are available in your project.

**Usage**

1.Import and use the TextEditor component in your React application:


import TextEditor from './TextEditor';

function App() {
  return (
    <div>
      <TextEditor />
    </div>
  );
}

export default App;


2. The component uses localStorage to persist user preferences and text content. You can clear this storage if you want to reset the state.


**Props**

**FontSelector:**

1.selectedFont (string): Currently selected font family.

2.onFontChange (function): Callback function to handle font change.

**FontWeightSelector:**

1.selectedFont (string): Currently selected font family.

2.selectedWeight (string): Currently selected font weight.

3.onWeightChange (function): Callback function to handle font weight change.

**CSS Styling**
The component uses the following classes for styling:

1.text-editor-container': Centers the entire text editor vertically and horizontally.

2.select-container': Container for font selection controls.

3.select-row: Flex container for aligning label and controls in a row.

4.text-area: Style for the textarea element.

5.button-container: Container for save and reset buttons.

6.button-save: Style for the save button.

7.button-reset: Style for the reset button.

8.save-message: Style for displaying feedback messages


**Images**

![image](https://github.com/user-attachments/assets/93ddc59d-7bae-4629-8489-a859dec8011d)


![image](https://github.com/user-attachments/assets/3c8c8fb1-bb88-4e55-a88a-9ce8bf76306d)


![image](https://github.com/user-attachments/assets/7967a8ce-85d6-43ff-8f4d-8ffc883b1a48)




