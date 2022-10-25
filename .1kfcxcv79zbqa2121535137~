// Get elemet by document
const btn = document.getElementById("btn");
const audio = document.getElementById("audio");

// classList of btn
const list = btn.classList;

// add class in btn
list.add("fa-solid");
list.add("fa-4x");
list.add("fa-play");

btn.addEventListener("click", function () {
  if (btn.classList.value == "fa-solid fa-4x fa-play") {
    // play to pause btn
    list.remove("fa-play");
    list.add("fa-pause");
    // Animation
    document.getElementById("track").style.animation =
      "carMove linear 13s infinite";
    document.getElementById("car").style.animation =
      "shake linear 0.3s infinite";
    document.getElementById("Wheel1").style.animation =
      "wheelRotation linear 0.16s infinite";
    document.getElementById("Wheel2").style.animation =
      "wheelRotation linear 0.16s infinite";
    // Audio
    audio.setAttribute("src", "sound.mp3");
  } else {
    // pause to play btn
    btn.classList.remove("fa-pause");
    btn.classList.add("fa-play");
    // Animation
    document.getElementById("track").style.animation = "";
    document.getElementById("car").style.animation = "";
    document.getElementById("Wheel1").style.animation = "";
    document.getElementById("Wheel2").style.animation = "";
    // Audio
    audio.setAttribute("src", "");
  }
});
