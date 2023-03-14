# DeliveryDriver2D
Unity and C# learning project

The goal of this project is to guide the car to pick up cargo (pink squares) and deliver it in the delivery area (blue zone), without hitting any of the obstacles (trees, rocks and houses).
In case one of the obstacles is hit, the car's speed reduces and it is only restored when the car passes over a "booster" (orange circle). To play, we must use the keys "left arrow" to move the car to the left, "right arrow" to move the car to the right, "up arrow" to move the car up, and "down arrow" to move the car down.

One level was developed to practice some basic functionalities from Unity and C# such as the features and methods listed below: 
><p>Transform.Translate()</p>
><p>[SerializeField]</p>
><p>Input.GetAxis()</p>
><p>Time.deltaTime()</p>
><p>Colliders and Rigidbodies</p>
><p>OnCollisionEnter2D()</p>
><p>OnTriggerEnter2D()</p>
><p>Assets</p>
><p>Follow Camera</p>
><p>Tags</p>
><p>GetComponent</p>

This is a demonstration of a player picking up cargo and deliverying to the blue zone. When the player hits an obstacle, the car slows down and only has its speed restored when goes over the booster:
>![alt text](https://github.com/wellingtonesposito/DeliveryDriver2D/blob/main/Delivery%20Driver%20Demo.gif "Demonstrative gif")
