# Code-Editor
A responsive web based code editor built using React. The @uiw/react-codemirror package is reponsible for building & customising the code editors. The app is divided into two sections, editor & simulator containers. The editor container consists of 3 editors each for HTML, CSS & JS. The simulator is an iframe view, where the code from the editors, compile down to render website inside it.

# Features
<ul> 
  <li>Write and edit HTML, CSS, and JavaScript code in a live editor.
  <li>See the live preview of your code output.</li>
  <li>Responsive design for both desktop and mobile devices.</li>
  <li>Theme for the app is inspired by MacOS.</li>
  <li>Editors have 3 toolbar buttons - Reset, Save & Expand/Collapse.</li>
  <li>🔴 Reset on click, reveals a dropdown, from where the user can clear the editor or reset it to the default template.</li>
  <li>🟡 Save is used to save the contents of the editors as respective(.html/.css/.js) files.</li>
  <li>🟢 Expand/Collapse as the name suggests, expands or collapses the editor.</li>
  <li>Contents of the editors are synced to local storage 😮 to prevent data loss on page reload.</li>
  <li>Each Re-render happens every 250ms to efficiently render content instead of re-rendering on each keystroke on the editors.</li>
  <li>Cool animations 🎭 and effects make the user experience awesome.</li></li>
</ul>
