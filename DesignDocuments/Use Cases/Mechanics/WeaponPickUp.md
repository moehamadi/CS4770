Title: Weapon Pick up

Description: Player can pick up weapons placed in the levels while in the human form.

Actors: User

Triggers: Player passes through weapon while in human form.

Preconditions: Player is alive and in human form.

Postconditions: Players has new weapon and is able to use it in human form.

Normal Flow:

    1.Player passes through weapons location.
    2.Engine checks that character is in human form.
    3.Weapon replaces players current weapon.
    4.Player is able to use weapon until ammo runs out.

Alternative Flow:<br>
&nbsp;&nbsp;&nbsp;&nbsp;4.a) Player's weapon runs out of ammo.<br>
	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1. Player loses weapon and has it replaced with basic weapon.<br>
&nbsp;&nbsp;&nbsp;&nbsp;4.b) Player passes over new weapon before ammo runs out.<br>
	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1. Player's current weapon is replaced with new weapon.<br>
