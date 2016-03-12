# VINCENT_MaximeBjtuGameClass
Repository fro game design classes bjtu 2016

Name: VINCENT Maxime Jean-Marie
Student ID: 15 12 90 71

Type of game: Vertical Scrolling 2D Shooter (Shoot them Up)

Rules:
	-The player has a character that can move in 2D (left-right/Up-Down)
	
	-The character has a limited amount of lives
	
	-The character can shoot missiles
	
	-Enemies appear from the sides on the upper half of the screen
		
	-Enemies move with specific patterns in 2D (enemy type X has X move pattern)
	
	-Enemies shoot missiles toward the playable character
	
	-Missiles can be different sizes but not less than what is visible and not more than what is acceptably avoidable (no half the screen size missiles)
	
	-If an enemy missile touches the Hitbox of the playable character, it loses a life
	
	-If the player missile touches an enemy, he loses hitpoints
	
	-When an enemy has 0 hitpoints or less, he dies
	
	-When an enemy dies, points add up to the player score
	
	-At specific scores, the player gains a new life (Example: 20000pts, 50000pts and 130000pts)
	
	-if the player has no life left, he looses the game
	
	-if an enemy collides with the player it counts as a missile hit and the player loses a life
	
	-The player cannot go outside of the border of the visible screen
	
	-Enemies can go outside of the playable borders, once they are outside they don't exist anymore
	
	-After a set ammount of enemies flew by (being killed or not) comes a boss character
	
	-Boss characters have much more hitpoints than normal enemies
	
	-Boss characters trigger a music event (music changes)
		
	-Boss characters may have sprite events
	 	(sprite or background change depending on attack or damages taken)
	
	-When a boss character dies, the level ends, the player score is shown and next level is playable
	
	-If last level is finished, player score shows with EndGame screen
	
