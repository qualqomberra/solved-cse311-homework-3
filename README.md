Download Link: https://assignmentchef.com/product/solved-cse311-homework-3
<br>
<h1>1.     Do Not Iron While Wearing Shirt</h1>

For each of the following English statements, (i) translate it into predicate logic, (ii) write the negation of that statement in predicate logic with the negation symbols pushed as far in as possible, and then (iii) translate the result of (ii) back to (natural) English.

Let the domain of discourse be people and activities. You should use only the predicates Loves(<em><sub>x,y</sub></em><sub>) </sub>and Likes(<em><sub>x,y</sub></em><sub>) </sub>which say that person <em>x </em>loves or likes (respectively) activity <em>y</em>; the predicates Person(<em><sub>x</sub></em><sub>) </sub>and Activity(<em><sub>x</sub></em><sub>)</sub>, which say whether <em>x </em>is a person or activity, respectively; and the predicates <em>x </em><sub>= <em>y </em></sub>and <em>x </em><sub>6= <em>y</em></sub>, which say whether or not <em>x </em>and <em>y </em>are the same object. You can use constants to refer to specific people or activities such as the “Bob” in the next example.

Example: “There is some activity, other than ironing, that Bob likes.’

<ol>

 <li>∃<em>x</em>((Activity(<em>x</em>) ∧ (<em>x </em>6= ironing)) ∧ Likes(Bob<em>,x</em>)) ii. ∀<em>x</em>((Activity(<em>x</em>) ∧ (<em>x </em>6= ironing)) →¬ Likes(Bob<em>,x</em>))</li>

</ol>

(Make sure you see why! It’s important to notice domain restrictions when translating to English.) iii. Bob does not like any activity other than ironing.

(Or less natural: Every activity other than ironing is not liked by Bob.) (a) [9 Points] Every activity that Bob loves is also loved by someone else.

(b) Someone who likes every activity does not love any activity.

<h1>2.     May Cause Drowsiness</h1>

Write formal proofs of each of the following.

<ul>

 <li>Given <em>p </em>∧ <em><sub>q</sub></em>, <em>p </em>→ <em><sub>r</sub></em>, and <em>r </em>→ <sub>(<em>s </em></sub>∧ <em><sub>w</sub></em><sub>)</sub>, it follows that <em>q </em>∧ <em><sub>w</sub></em>.</li>

 <li>Given <em>p </em>→ <em>q</em>, <em>r </em>→¬<em>p</em>, and (¬<em>r </em>∧ <em>q</em>) → <em>s</em>, it follows that <em>p </em>→ <em>s</em>.</li>

 <li>Given ((<em>p </em>∧ <em>q</em>) → (<em>p </em>∧ <em>r</em>)) ∧ ((<em>p </em>∧ <em>r</em>) → (<em>p </em>∧ <em>q</em>)), it follows that <em>p </em>→ ((<em>q </em>→ <em>r</em>) ∧ (<em>r </em>→ <em>q</em>)).</li>

</ul>

You can write your proofs by hand or in LATEX. Alternatively, feel free to use either of the following tools:

<ul>

 <li><a href="https://homes.cs.washington.edu/~kevinz/proof-test/">This tool</a> will allow you to check the correctness of most proofs in Propositional Logic. You can use it for these problems by typing in the premise and conclusion and clicking “Start Proof”. (You can take a screenshot of your completed proof and include it in your submission.)</li>

 <li><a href="https://cozyide.web.app/">Cozy IDE</a> now has a project template called “CSE 311 HW3” that is preloaded with these three problems.</li>

</ul>

(As in HW2, you can download your completed project as a zip file and submit it in canvas.)

(Both tools only allow one premise, but they can take the “∧” of those facts as the premise instead.)

<h1>3.     Contents Under Pressure</h1>

In this problem, we will consider the following, new inference rule:

This rule says that, if we know that either <em>A </em>or <em>B </em>is true and that both <em>A </em>implies <em>C </em>and <em>B </em>implies <em>C</em>, then it follows that <em>C </em>is true. If it is <em>A </em>that is true, then we get that <em>C </em>is true by Modus Ponens and likewise if <em>B </em>is true instead. This is a valid rule of inference and you are <strong>free to use it </strong>outside of this problem as well.

<ul>

 <li>Use the Proof By Cases rule to prove the following. Given <em>p </em><sub>∧ (<em>q </em>∨ <em>r</em>)</sub>, <em>q </em><sub>→ (<em>r </em>∧ <em>s</em>)</sub>, and <em>r </em>→ (<em>r </em>∧ <em>s</em>), it follows that <em>p </em>∧ (<em>s </em>∨ <em>t</em>)</li>

 <li>Prove that the “Elim ∨” rule follows from “Proof By Cases”. Specifically, use the Proof by Cases rule to prove that, given <em>p </em><sub>∨ <em>q </em></sub>and ¬<em><sub>p</sub></em>, it follows that <em>q </em>is true. (You may not use Elim ∨.)</li>

 <li>] What does (b) tell us about the relative power of “Elim ∨” versus “Proof By Cases” to infer new facts from given ones?</li>

</ul>

<h1>4.     Not Intended For Human Consumption</h1>

Let <em>Q</em><sub>(<em>x</em>) </sub>be a predicate defined in some, fixed domain of discourse.

<ul>

 <li>Prove that, given ¬(∀<em>y Q</em>(<em>y</em>)), it follows that ∃<em>x</em>(<em>Q</em>(<em>x</em>) →∀<em>y Q</em>(<em>y</em>)).</li>

 <li>Prove that, given ∀<em>y Q</em>(<em>y</em>), it follows that ∃<em>x</em>(<em>Q</em>(<em>x</em>) →∀<em>y Q</em>(<em>y</em>)).</li>

</ul>

<em>Hint</em>: It is okay to simply <strong>repeat </strong>a fact proved above, again, on another line below. Just cite the original line where it appeared as the explanation.

<ul>

 <li>Why can we conclude from parts (a) and (b) that ∃<em><sub>x</sub></em><sub>(<em>Q</em>(<em>x</em>) </sub>→∀<em><sub>y Q</sub></em><sub>(<em>y</em>)) </sub>is a tautology? Explain. (A formal proof is not necessary but is also allowed.)</li>

</ul>

<h1>5.     Keep Away From Small Children</h1>

Recall that an integer <em>n </em>is a <em>square </em>iff there exists a <em>k </em><sub>∈</sub>Z such that <em>n </em><sub>= <em>k</em></sub><sup>2</sup>. Formally, with our domain of discourse as the integers, we can define Square(<em><sub>n</sub></em><sub>) := </sub>∃<em><sub>k </sub></em><sub>(<em>n </em>= <em>k</em></sub><sup>2</sup><sub>)</sub>.

<ul>

 <li>Write the following claim in Predicate Logic: if integers <em>n </em>and <em>m </em>are squares, then <em>nm </em>is a square. (Be careful!)</li>

 <li>Give a formal proof of the claim from part (a). In addition to the inference rules discussed in class, you can also rewrite an algebraic expression to equivalent ones using the rule “Algebra”. (E.g., you could write “<em>a</em><sub>(<em>b </em>+ 1) </sub>− <em><sub>a </sub></em><sub>= <em>ab</em></sub>” with Algebra as the rule / explanation.)</li>

 <li>Translate your formal proof from part (b) into an English proof.</li>

</ul>

<h1>6.     Extra Credit: Some Assembly Required</h1>

In this problem, we will extend the machinery we used in HW1’s extra credit problem in two ways. First, we will add some new instructions. Second, and more importantly, we will add <em>type information </em>to each instruction.

Rather than having a machine with single bit registers, we will imagine that each register can store more complex values such as

<strong>Primitives </strong>These include values of types int, float, boolean, char, and String.

<strong>Pairs of values </strong>The type of a pair is denoted by writing “×” between the types of the two parts. For example, the pair (1<em><sub>,</sub></em>true) has type “int × boolean” since the first part is an int and the second part is a boolean.

<strong>Functions </strong>The type of a function is denoted by writing a “→” between the input and output types. For example, a function that takes an int as argument and returns a String is written “int → String”. We add type information, describing what is stored in each each register, in an additional column next to the instructions. For example, if <em>R</em><sub>1 </sub>contains a value of type int and <em>R</em><sub>2 </sub>contains a value of type int → <sub>(</sub>String×int), i.e., a function that takes an int as input and returns a pair containing a String and an int, then we could write the instruction

<em>R</em><sub>3 </sub>:= CALL(<em>R</em><sub>1</sub><em>,R</em><sub>2</sub>)                           String <sup>× </sup>int

which calls the function stored in <em>R</em><sub>2</sub>, passing in the value from <em>R</em><sub>1 </sub>as input, and stores the result in <em>R</em><sub>3</sub>, and write a type of “String × int” in the right column since that is the type that is now stored in <em>R</em><sub>3</sub>.

In addition to <sub>CALL</sub>, we add new instructions for working with pairs. If <em>R</em><sub>1 </sub>stores a pair of type String×int, then <sub>LEFT</sub><sub>(<em>R</em></sub><sub>1</sub><sub>) </sub>returns the String part and <sub>RIGHT</sub><sub>(<em>R</em></sub><sub>1</sub><sub>) </sub>returns the int part. If <em>R</em><sub>2 </sub>contains a char and <em>R</em><sub>3 </sub>contains a boolean, then <sub>PAIR</sub><sub>(<em>R</em></sub><sub>2</sub><em><sub>,R</sub></em><sub>3</sub><sub>) </sub>returns a pair of containing a char and a boolean, i.e., a value of type char × boolean.

<ul>

 <li>Complete the following set of instructions so that they compute, in the final register assigned, a value of type float × boolean:</li>

</ul>

<em>R</em><sub>1                                                </sub>int × float

<em>R</em><sub>2                                                 </sub>int → String

<em>R</em><sub>3                                                 </sub>String → <sub>(</sub>char × boolean)

<em>R</em><sub>4 </sub>:= <em>…                           …</em>

The first three lines show the types <strong>already stored </strong>in registers <em>R</em><sub>1</sub>, <em>R</em><sub>2</sub>, and <em>R</em><sub>3 </sub>at the start, before your instructions are executed. You are free to use the values in those registers in later instructions.

Since we have unlimited space, store into a <em>new register </em>on each line. <strong>Do not reassign </strong>any registers.

<ul>

 <li>Compare the types listed next to these instructions to the propositions listed on the lines of your proof in problem 2 (a). Give a collection of text substitutions, such as replacing all instances of “<em>p</em>” by “int” (these can include both atomic propositions and operators), that will make the sequence of propositions in problem 2 (a) <em>exactly match </em>the sequence of types in problem 6 (a). You may need to change your solution to problem 6 (a) slightly to make this work.</li>

 <li>Now, let’s add another way to form new types. If <em>A </em>and <em>B </em>are types, then <em>A </em><sub>+ <em>B </em></sub>will be the type representing values that can be of either type <em>A </em>or type <em>B</em>. For example, String + int would be a type of values that can be strings or integers.</li>

</ul>

To work with this new type, we need some new instructions. First, if <em>R</em><sub>1 </sub>has type <em>A</em>, then the instruction <sub>CASE</sub><sub>(<em>R</em></sub><sub>1</sub><sub>) </sub>returns the same value but now having type <em>A </em><sub>+ <em>B</em></sub>. (Note that we can pick any type <em>B </em>that we want here.) Second, if <em>R</em><sub>2 </sub>stores a value of type <em>A </em><sub>+ <em>B</em></sub>, <em>R</em><sub>3 </sub>stores a function of type <em>A </em><sub>→ <em>C </em></sub>(a function taking an <em>A </em>as input and returning a value of type <em>C</em>), and <em>R</em><sub>4 </sub>stores a function of type <em>B </em>→ <em><sub>C</sub></em>, then the instruction <sub>SWITCH</sub><sub>(<em>R</em></sub><sub>2</sub><em><sub>,R</sub></em><sub>3</sub><em><sub>,R</sub></em><sub>4</sub><sub>) </sub>returns a value of type <em>C</em>: it looks at the value in <em>R</em><sub>2</sub>, and, if it is of type <em>A</em>, it calls the function in <em>R</em><sub>3 </sub>and returns the result, whereas, if it is of type <em>B</em>, it calls the function in <em>R</em><sub>4 </sub>and returns the result. In either case, the result is something of type <em>C</em>.

Complete the following set of instructions so that they compute, in the final register assigned, a value of type int × <sub>(</sub>char + boolean):

<em>R</em><sub>1                                                  </sub>int × (float + String)

<em>R</em><sub>2     </sub>float → (String × char) <em>R</em><sub>3    </sub>String → (String × char)

<em>R</em><sub>4 </sub>:= <em>…                           …</em>

The first three lines again show the types of values already stored in registers <em>R</em><sub>1</sub>, <em>R</em><sub>2</sub>, and <em>R</em><sub>3</sub>. As before, do not reassign any registers. Use a new register for each instruction’s result.

<ul>

 <li>Compare the types listed next to these instructions to the propositions listed on the lines of your proof in problem 3 (a). Give a collection of text substitutions, such as replacing all instances of “<em>p</em>” by “int” (these can include both atomic propositions and operators), that will make the sequence of propositions in problem 3 (a) <em>exactly match </em>the sequence of types in problem 6 (c). You may need to change your solution to problem 6 (c) slightly to make this work.</li>

 <li>Now that we see how to match up the propositions in our earlier proofs with types in the code above, let’s look at the other two columns. Describe how to translate each of the rules of inference used in the proofs from both problem 2 (a) and 3(a) so that they turn into the instructions in problem 6 (a) and (c).</li>

 <li>One of the important rules <strong>not </strong>used in problems 2 (a) or 3 (a) was Direct Proof. What new concept would we need to introduce to our assembly language so that the similarities noted above apply could also to proofs that use Direct Proof?</li>

</ul>