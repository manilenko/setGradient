this js file use DOM manipulation for set Gradient( set body.style.background)

#function

function setGradient() {
   body.style.background =
      "linear-gradient(to right, "
      + color1.value
      + ", "
      + color2.value
      + ")";

   css.textContent = body.style.background + ";";

}
