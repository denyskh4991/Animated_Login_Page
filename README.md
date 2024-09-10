# Modern Login Page

<p>The **Modern Login Page** is a stylish and user-friendly interface designed to provide users with seamless sign-in and sign-up functionalities. It utilizes HTML, CSS, and JavaScript to deliver a sleek, interactive design that toggles between login and registration forms with a dynamic animation effect.</p>
<h2>Key Features</h2>
<h3>Login and Registration Forms</h3>
<p>The page contains two forms: one for users to sign in and another to create an account. The transition between these two forms is smooth, offering a seamless experience as users toggle between the sections.</p>
<h3>Social Media Login</h3>
<h4>Social Media Icons</h4>
<p>Both the login and registration forms include options for users to sign in via popular social media platforms like Google, Facebook, GitHub, and LinkedIn, represented by icons.</p>
<h4>Form Inputs</h4>
<p>The login form allows users to input their email and password, while the registration form asks for their name, email, and password, making account creation simple and intuitive.</p>
<h4>Control Buttons</h4>
<p>The "Sign In" and "Sign Up" buttons activate the respective form actions. Additionally, users can click on the “Forget Your Password” link to recover access to their account.</p>
<h3>Visual Design</h3>
<p>The page sports a modern look with a linear gradient background in soft colors, transitioning from light grey to a pale blue. The form container is centered on the screen, with rounded corners and a shadow effect, giving it a polished, elevated feel.</p>
<h4>Typography and Icons</h4>
<p>The page uses the **Montserrat** font, which enhances its contemporary aesthetic. Social media icons from FontAwesome are incorporated, adding a professional touch.</p>
<h3>Responsive Design</h3>
<p>The layout is fully responsive, adjusting to different screen sizes, making it functional on both desktop and mobile devices.</p>
<h2>Technical Overview</h2>
<h3>HTML Structure</h3>
<p>The HTML includes two main forms housed within a container. Each form is wrapped inside a `div` for login and signup, with buttons and icons for interactivity.</p>
<h3>CSS Styling</h3>
<p>The CSS is used to achieve a clean and modern layout. It incorporates linear gradients, flexbox alignment, and transitions for the animated toggle between the forms.</p>
<h4>Animations and Transitions</h4>
<p>The form toggle is implemented with CSS animations, allowing a smooth transition when switching between the login and registration views.</p> 
<h3>JavaScript Functionality</h3> 
<p>JavaScript is used to control the form toggle. Event listeners on the "Sign Up" and "Sign In" buttons dynamically apply an "active" class to the container, triggering the animation and revealing the appropriate form.</p>

    const registerBtn = document.getElementById('register');
    const loginBtn = document.getElementById('login');
    
    registerBtn.addEventListener('click', () => {
        container.classList.add("active");
    });
    
    loginBtn.addEventListener('click', () => {
        container.classList.remove("active");
    });

<h2>Conclusion</h2>
<p>The **Modern Login Page** provides an aesthetically pleasing, user-friendly interface that simplifies the login and registration process. With responsive design, smooth transitions, and social media integration, it offers a professional experience suitable for modern web applications.</p>
