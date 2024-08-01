# Sign in / Sign up Form

This is a simple sign in and sign up form with a stylish transition between the two. It uses HTML, CSS, and JavaScript to create a smooth user experience. The design is responsive and works well on both desktop and mobile devices.

## Features

- **Responsive Design**: Works on all screen sizes.
- **Smooth Transitions**: Uses CSS transitions for a sleek look.
- **Form Validation**: Basic form validation using HTML5.
- **Font Awesome Icons**: Includes icons from Font Awesome.

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Font Awesome

## How to Use

1. Clone the repository:
    ```
    git clone https://github.com/yourusername/your-repo-name.git
    ```
2. Open `index.html` in your browser to view the form.

## Code Explanation

### HTML Structure

The HTML file consists of two main sections: the sign-up container and the sign-in container. These are placed inside a main container which handles the transitions.

```html
<div class="container" id="container">
    <!-- Sign Up Form -->
    <div class="form-container sign-up-container">
        <form action="#">
            <h1>Create Account</h1>
            <span>or use your email for registration</span>
            <input type="text" placeholder="Name" />
            <input type="email" placeholder="Email" />
            <input type="password" placeholder="Password" />
            <button>Sign Up</button>
        </form>
    </div>
    <!-- Sign In Form -->
    <div class="form-container sign-in-container">
        <form action="#">
            <h1>Sign in</h1>
            <span>or use your account</span>
            <input type="email" placeholder="Email" />
            <input type="password" placeholder="Password" />
            <a href="#">Forgot your password?</a>
            <button>Sign In</button>
        </form>
    </div>
    <!-- Overlay for transition -->
    <div class="overlay-container">
        <div class="overlay">
            <div class="overlay-panel overlay-left">
                <h1>Welcome Back!</h1>
                <p>To keep connected with us please login with your personal info</p>
                <button class="ghost" id="signIn">Sign In</button>
            </div>
            <div class="overlay-panel overlay-right">
                <h1>Hello, Friend!</h1>
                <p>Enter your personal details and start journey with us</p>
                <button class="ghost" id="signUp">Sign Up</button>
            </div>
        </div>
    </div>
</div>
