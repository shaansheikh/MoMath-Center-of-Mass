# MoMath Hackathon 2017: Polygon Center of Mass

- Project category: _Math Square behavior_
- Team members: Brian Sapozhnikov <brian.sapozhnikov@gmail.com>,  Lise Ho <lise.ho6@gmail.com>, Shaan Sheikh <shaansweb@gmail.com>, Mary Taft <mary.taft97@gmail.com>

## Intro

This is an interactive demo of center of mass for the MoMath Math Square exhibit. This was created at the MoMath _Expressions_ hackathon on August 5th and 6th, 2017.

## Installation and Usage

Git clone the repo, run `npm install`, run `npm run-script dev`, and type "center-of-mass" in behavior. Our behavior file is located in behs/center-of-mass.js. For more details, see the [MoMath Math Square SDK](https://github.com/momathtech/math-square/blob/master/README.md).

## The Math

The purpose of the project is to create an interactive demonstration that intuitively conveys the concept of a center of mass of a polygon. The center of mass has many applications in both Geometry and Physics. In our demo, we create a polygon with the positions of all visitors on the Math Square as verticies. The center of mass of the polygon is shown on the screen, along with lines connecting it to each user on the Square, intuitively conveying that visitors' poitions influence the position of the center of mass. A ring is shown on the square, and visitors must collaborate to move the center of mass within the ring. Once this goal is achieved, we rotate the polygon around the ring to convey how the center of mass is the point around which a freely rotating object with a angular velocity will rotate. A new ring is then set as the target.

## The Submission

We expect our exhibit will be especially educational for elementary and middle school age children, though all ages will find it to be fun and a learning experience. It requires collaboration and communication between visitors. However, not all visitors on the square need to participate in achieving the goal for the goal to be reached, as others can compensate for their movements. This makes it ideal for when there are multiple people of a variety of ages on the board. This may be even be more educational for older students attempting to achieve the goal because the must learn how the center of mass behaves when you have limited control of the polygon verticies.

To make it clearer the users need to get the center of mass to the target ring, the color of the polygon is determined by the distance between the center of mass and ring. The close visitors manage to bring the center of mass, the more green the polygon becomes. The further it gets, the bluer it becomes.

## Additional Notes

