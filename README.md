turnLeft();
for (var count = 0; count < 2; count++) {
  moveForward();
}
turnRight();
moveForward();
turnLeft();
moveForward();
placeBlock("tnt");
turnRight();
turnRight();
for (var count2 = 0; count2 < 9; count2++) {
  moveForward();
}
turnLeft();
for (var count3 = 0; count3 < 4; count3++) {
  moveForward();
}
turnLeft();
for (var count4 = 0; count4 < 2; count4++) {
  ifBlockAhead("water", function() {
    placeBlockAhead("grass");
  });
  moveForward();
}
turnRight();
for (var count5 = 0; count5 < 4; count5++) {
  placeBlock("tnt");
  moveForward();
}
for (var count6 = 0; count6 < 2; count6++) {
  turnRight();
  moveForward();
}
turnLeft();
