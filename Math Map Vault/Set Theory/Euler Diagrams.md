#set_theory 

# Euler Diagrams

---

Now that we've got the basics of sets, elements, and membership down, it'll be very helpful to be able to represent these concepts graphically. **Euler diagrams** allow us to do this by representing sets as circles. We actually can use any closed shape, such as a square, a triangle, or an ellipse, but circles are the standard shape we use. We then write the elements of a set inside of the circle which represents it.

For example, say we have the set $S = \{a, b, c\}$. We could represent this set using an Euler diagram like so:

<html>
	<center>
		<svg width="200" height="200">
			<circle cx="100" cy="100" r="90" stroke="white" stroke-width="4" fill="none"/>
			<text x="25" y="25" fill="white">S</text>
			<text x="90" y="80" fill="white">a</text>
			<text x="70" y="130" fill="white">b</text>
			<text x="120" y="110" fill="white">c</text>
		</svg>
	</center>
</html>

The set is the white circle labeled $S$. The elements $a$, $b$, and $c$ collected within $S$ are drawn inside of the circle representing $S$.

---

We can represent multiple sets by using multiple circles. Say we have the sets

- $A = \{l, m\}$
- $B = \{n, o\}$

We can represent them with an Euler diagram like so:

<html>
	<center>
		<svg width="500" height="200">
			<circle cx="100" cy="100" r="90" stroke="red" stroke-width="4" fill="none"/>
			<circle cx="400" cy="100" r="90" stroke="blue" stroke-width="4" fill="none"/>
			<text x="25" y="25" fill="red">A</text>
			<text x="90" y="80" fill="red">l</text>
			<text x="70" y="130" fill="red">m</text>
			<text x="465" y="25" fill="blue">B</text>
			<text x="425" y="140" fill="blue">n</text>
			<text x="370" y="100" fill="blue">o</text>
		</svg>
	</center>
</html>

The red circle represents the set $A$, and the red elements $l$ and $m$ drawn inside the circle belong to the set $A$. The blue circle represents the set $B$, and the blue elements $n$ and $o$ drawn within that circle belong to the set $B$. Although I often color my Euler diagrams to make it clear which elements belong to which sets, it's unnecessary. Euler diagrams could also be created using only one color.

---

If two sets share an element or multiple elements, we'll want to show this by overlapping the two circles, and placing the shared element(s) inside the overlapping region. Say our sets are

- $C = \{p, q, r\}$
- $D = \{q, r, s, t\}$
- $E = \{t, u, v\}$

$C$ and $D$ share the elements $q$ and $r$, and $D$ and $E$ share the element $t$. We could show this using an Euler diagram like so:

<html>
	<center>
		<svg width="500" height="250">
			<circle cx="120" cy="100" r="90" stroke="blue" stroke-width="4" fill="none"/>
			<ellipse cx="250" cy="100" rx='110' ry="90" stroke="red" stroke-width="4" fill="none"/>
			<circle cx="380" cy="100" r="90" stroke="yellow" stroke-width="4" fill="none"/>
			
			<text x="45" y="25" fill="blue">C</text>
			<text x="300" y="15" fill="red">D</text>
			<text x="445" y="25" fill="yellow">E</text>
			
			<text x="90" y="80" fill="blue">p</text>
			<text x="165" y="90" fill="purple">q</text>
			<text x="170" y="130" fill="purple">r</text>
			<text x="250" y="60" fill="red">s</text>
			<text x="325" y="110" fill="orange">t</text>
			<text x="400" y="65" fill="yellow">u</text>
			<text x="425" y="140" fill="yellow">v</text>
		</svg>
	</center>
</html>

Set $C$ is represented by the blue circle, set $D$ is represented by the red ellipse, and set $E$ is represented by the yellow circle. We could have used a circle for set $D$, but using an ellipse makes the diagram look neater. Reading the diagram, we see that:

- $p \in C$
- $q, r \in C$ and $q, r \in D$
- $s \in D$
- $t \in D$ and $t \in E$
- $u, v \in E$

I colored $q$ and $r$ purple to show that they belonged to both the blue and red sets, and I colored $t$ orange to show that it belonged to both the red and yellow sets. However, as mentioned above, Euler diagrams can also be done without coloring. Without coloring, the above diagram would look like this:

<html>
	<center>
		<svg width="500" height="250">
			<circle cx="120" cy="100" r="90" stroke="white" stroke-width="4" fill="none"/>
			<ellipse cx="250" cy="100" rx='110' ry="90" stroke="white" stroke-width="4" fill="none"/>
			<circle cx="380" cy="100" r="90" stroke="white" stroke-width="4" fill="none"/>
			
			<text x="45" y="25" fill="white">C</text>
			<text x="300" y="15" fill="white">D</text>
			<text x="445" y="25" fill="white">E</text>
			
			<text x="90" y="80" fill="white">p</text>
			<text x="165" y="90" fill="white">q</text>
			<text x="170" y="130" fill="white">r</text>
			<text x="250" y="60" fill="white">s</text>
			<text x="325" y="110" fill="white">t</text>
			<text x="400" y="65" fill="white">u</text>
			<text x="425" y="140" fill="white">v</text>
		</svg>
	</center>
</html>

Without color, it's more difficult to read (especially for beginners). However, the same information is being conveyed, so there's no technical difference between colored and uncolored diagrams.

---

Let's practice reading an Euler diagram and figuring out which elements belong to which sets:

<html>
	<center>
		<svg width="400" height="250">
			<ellipse cx="110" cy="100" rx="100" ry="90" stroke="blue" stroke-width="4" fill="none"/>
			<ellipse cx="280" cy="100" rx='110' ry="90" stroke="red" stroke-width="4" fill="none"/>
			<circle cx="320" cy="120" r="45" stroke="yellow" stroke-width="4" fill="none"/>
			
			<text x="25" y="25" fill="blue">M</text>
			<text x="355" y="25" fill="red">N</text>
			<text x="265" y="90" fill="yellow">O</text>
			
			<text x="50" y="80" fill="blue">f</text>
			<text x="125" y="70" fill="blue">g</text>
			<text x="100" y="130" fill="blue">h</text>
			<text x="185" y="100" fill="purple">w</text>
			<text x="255" y="50" fill="red">x</text>
			<text x="295" y="120" fill="orange">y</text>
			<text x="325" y="135" fill="orange">z</text>
		</svg>
	</center>
</html>

Here, we can see that we have three sets: $M$ is blue, $N$ is red, and $O$ is yellow. We can also see that

- $f,~g,~h \in M$
- $w \in M$ and $w \in N$
- $x \in N$
- $y, z \in N$ and $y, z \in O$

So our three sets look like this:

- $M = \{f, g, h, w\}$
- $N = \{w, x, y, z\}$
- $O = \{y, z\}$

Note that there are no yellow elements because there are no elements belonging only to $O$ that are not also inside of some other set. I colored all of the elements in $O$ orange to show that they were also contained within the red set $N$. Because $O$ does not contain any elements that are not contained within $N$, we draw the circle representing $O$ completely inside of the ellipse representing $N$.

---

Next: [[Universe]]