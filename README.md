# Charity-water/* Simple, beginner-friendly CSS for charity: water landing page */

/* Body styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f7f7f7;
    color: #333;
}

/* Navigation bar styles */
nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #FFC907; /* Brand yellow */
    padding: 10px 20px;
}

/* Hamburger icon styles */
.hamburger {
    display: flex;
    flex-direction: column;
    justify-content: center;
    cursor: pointer;
    height: 32px;
    width: 32px;
}
.hamburger .bar {
    width: 28px;
    height: 4px;
    background: #032B44; /* Navy blue */
    margin: 4px 0;
    border-radius: 2px;
}

/* Hero section styles */
.hero {
    text-align: center;
    margin: 30px 0;
}
.hero h1 {
    color: #FFC907; /* Brand yellow */
    font-size: 2.5em;
    margin-bottom: 10px;
}

/* Story section styles */
.story {
    max-width: 600px;
    margin: 0 auto 30px auto;
    padding: 0 10px;
}
.story h2 {
    color: #2E9DF7; /* Brand blue */
}

/* Impact story section styles */
.impact-story {
    max-width: 600px;
    margin: 0 auto 30px auto;
    padding: 0 10px;
}
.impact-content {
    display: flex;
    align-items: center;
}
.impact-image {
    width: 120px;
    height: auto;
    border-radius: 8px;
    margin-right: 20px;
}

/* Call-to-action section styles */
.call-to-action {
    text-align: center;
    margin: 30px 0;
}
.donate-button {
    display: inline-block;
    background-color: #2E9DF7;
    color: #fff;
    padding: 12px 24px;
    border-radius: 5px;
    text-decoration: none;
    font-weight: bold;
    margin-top: 10px;
}
