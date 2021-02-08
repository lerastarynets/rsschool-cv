1. Starynets Valeriia
2. Email: *starynetsv@gmail.com*
3. I have no experienc, however, I managed to learn HTML, CSS and JavaScript basics on my own. I want to gain insight into JavaScript, learn React and start IT career.\
I am skilful at Math and able to learn quickly. My number one priority is to find a job in IT field.
4. JavaScript, Git
5. ```
      var getRandomNumber = function (size) {
      return Math.floor(Math.random() * size);
    };

    // Calculate distance between click event and target\
    var getDistance = function (event, target) {
      var diffX = event.offsetX - target.x;
      var diffY = event.offsetY - target.y;
      return Math.sqrt((diffX * diffX) + (diffY * diffY));
    };

    // Get a string representing the distance\
    var getDistanceHint = function (distance) {
      if (distance < 10) {
        return "Huya pichot";
      } else if (distance < 20) {
        return "Very hot";
      } else if (distance < 40) {
        return "Hot";
      } else if (distance < 80) {
        return "Norm, no ti lalka";
      } else if (distance < 160) {
        return "Cold";
      } else if (distance < 320) {
        return "Ochen cold";
      } else if (distance < 500) {
        return "Ochen silno cold";
      } 
      else if (distance < 700) {
        return "Ti zamerz!";
      } 
      else {
        return "You are loh!";
      }
    };

    // Set up our variables
    var width = 800;
    var height = 800;
    var clicks = 20;

    // Create a random target location
    var target = {
      x: getRandomNumber(width),
      y: getRandomNumber(height)
    };

    // Add a click handler to the img element
    $("#map").click(function (event) {
      clicks--;

      // Get distance between click event and target
      var distance = getDistance(event, target);
      // Convert distance to a hint
      var distanceHint = getDistanceHint(distance);

      // Update the #distance element with the new hint
      $("#distance").text(distanceHint);
      $("#cliki").text("U HAVE "+clicks+" CLIKOV LEFT!");
      // If the click was close enough, tell them they won
      if (distance < 8) {
        alert("Ti nashel zakladku! Ti zausal " + clicks + " clicks!");
      }
      if (clicks < 1) {
        alert("Game over, daun! Cliki konchilis!");
        return;
      }
    });
    ```
6. 
7. Education:
    * High School
    * University
    * JavaScript course: https://www.youtube.com/playlist?list=PLcvhF2Wqh7DPD5sRK3lw4bjBsKdgY2bPi
    * Books:
        1. HTML & CSS Headfirst
        2. JavaScript for kids
        3. Grokking Algorithms
8. I have a CAE certificates which means my level is C1
