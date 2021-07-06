# Google-Font-Light-Dark-Mode-Toggle-Clone

Implemented Light/Dark toggle using CSS and Javascript. 

Calling a function to set LightMode or DarkMode based on condition.
```
function enableDarkMode() {
  document.body.classList.remove("light-theme")
  document.body.classList.add("dark-theme")
  themeToggle.setAttribute("aria-label", "Switch to light theme")
}

function enableLightMode() {
  document.body.classList.remove("dark-theme")
  document.body.classList.add("light-theme")
  themeToggle.setAttribute("aria-label", "Switch to dark theme")
}
```
