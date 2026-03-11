# Kim_Sia_Midterm
let stars = [];
let numStars = 100;

function setup() {
createCanvas(800,600);

for(let i =0; i < numStars; i++) {
stars.push(new Star(random(width), random(height))):
}
}
