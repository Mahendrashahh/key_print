# KeyPress Fun with JavaScript 🎉

## Description
Ye project ek **fun aur learning purpose** ka example hai jisme hum **JavaScript ka `keydown` event listener`** use karte hain. Isse aap seekh sakte ho ki keyboard events ko kaise detect aur handle karte hain.  

---

## Features
- `window.addEventListener` ka use karke keyboard events detect karna  
- Har pressed key ko **console** me show karna  
- Fun aur interactive learning purpose ke liye simple behavior  

---

## How It Works
1. Page load hote hi **window** par event listener lag jaata hai.  
2. Jab koi key press hoti hai, `keydown` function trigger hota hai.  
3. Pressed key ka naam console me print hota hai.  

```javascript
window.addEventListener("keydown", function(event) {
    console.log("You pressed: " + event.key);
});
