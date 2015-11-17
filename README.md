# assignment 4

Fixed the box fixtures such that the fixtures will each collide with
both one another and the floor.

This was done by modifying the following line --
	fixtureDef.filter.maskBits = WORLD_ENTITY;
to:
	fixtureDef.filter.maskBits = WORLD_ENTITY|PHYSICS_ENTITY;

for both the fixtures.
