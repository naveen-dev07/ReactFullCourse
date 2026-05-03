Method 1: The Modern Way (Recommended for Repos)
This uses Vite, which is the fastest and most modern way to build React sites.

Step 1: Install Node.js
You must have Node.js installed to use React tools.

Download it from - nodejs.org.

Verify it works by typing node -v in your terminal/command prompt.


Step 2: Create the Project
Open your terminal and run:


Step 3: Install Dependencies
Inside your project folder, run:


Method 2: Adding React to an Existing HTML Page
If you don't want a full project structure and just want to "call" React in your current file:

<!-- Container for React -->
<div id="root"></div>

<!-- Load React scripts -->
<script src="https://unpkg.com"></script>
<script src="https://unpkg.com"></script> // its a way to lode react using this web or there is another one if you search.

<!-- Your code -->
<script>
  const root = ReactDOM.createRoot(document.getElementById('root'));
  root.render(React.createElement('h1', null, 'Hello from React!'));// this is how it looks.Your first react code!
</script>
