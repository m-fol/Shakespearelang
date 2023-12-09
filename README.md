# A Quick Guide to Shakespeare Programming Language (SPL)
The Shakespeare Programming Language (SPL) is an esoteric programming language, emulating Shakespearean plays.

## Installation

This programming language can be installed in any compiler that supports Python.
Simply, through cmd (Windows), run the command:
```shakespeare
pip install shakespearelang
```

Make sure that if you are using PyCharm, to install the library through the compiler:
> You will have to go to File -> New Project Setup -> Settings for new Projects.

Install and import the library there, searching it by its name.

## Starting the Program
For a valid SPL, a title is always needed.
```shakespeare
Play Title, Description
```
The description of the play is marked as a comment and ignored.
## Setting Variables
Variables are named after Shakespearian characters.
```shakespeare
Name, Description
```
Likewise, the description is always ignored.

## Acts and Scenes
In the SPL programming language, an "act" is a major division of the program, representing a significant part of the overall script. Acts are used to structure the program into distinct segments, each with its own thematic focus or purpose.
```shakespeare
Act <Act Number>: <Act Title>
  # Code for the act goes here
```
Within each act, you have "scenes," which are smaller units of the program where specific actions or interactions take place. Scenes provide a way to organize the code further, allowing for a clear delineation of different stages within an act.
```shakespeare
Scene <Scene Number>: <Scene Title>
  # Code for the scene goes here
```
### Using Acts and Scenes Together:
Acts and scenes work together to create a structured and organized program. An act may contain multiple scenes, and each scene contributes to the overall narrative of that act. This structure helps make the code more readable, especially as the program grows in complexity.

Example:
```shakespeare
# Declare variables and initialize values
Act 1: Initialization
  Scene 1: Characters Appear
  [Enter <characters>]
    
  [Exit <characters>]
  Scene 2: Continuing
  [Enter <characters>]
   # Additional code
  [Exit <characters>]

```

> Remember! It's not necessary for a character to **exit** when a scene or an act ends!

## Entering, exiting and "exeunting" (is that a word?) Variables
In a Shakespeare-inspired programming language like SPL, the concepts of "Entering," "Exiting," and "Exeunting" are used to describe the introduction, conclusion, and termination of characters (variables) in the script. These terms add a theatrical and literary flair to the process of managing variables within the program.

### Entering Variables:

In SPL, the act of introducing a new variable is described as the character "entering" the stage. This is the point at which the variable is declared and given a role in the play. The introduction of variables is often done at the beginning of the program or within specific acts and scenes.

#### Syntax:

```shakespeare
<VariableName>, a <VariableType> with <VariableAttributes>.
```

#### Example:

```shakespeare
Romeo, a young man with remarkable patience.
Juliet, a young woman with an affinity for words.
```

### Exiting Variables:

Exiting a variable occurs when it is no longer needed in the scene. This is similar to a character leaving the stage after their role in the play is complete. In programming terms, this may involve deallocating memory or releasing resources associated with the variable.

#### Syntax:

```shakespeare
[Exit <VariableName>]
```

#### Example:

```shakespeare
[Exit Romeo]
```

### "Exeunting" Variables:

The term "Exeunt" is borrowed from theatrical language, where it is used to signal the exit of characters from the stage. In SPL, "Exeunt" is used to signify the end of a a block of code, an Act. It encapsulates the actions or interactions involving that variable within a scene or act.

#### Syntax:

```shakespeare
[Exeunt]
```

#### Example:

```shakespeare
Act 1: Testing
[Enter Romeo and Juliet]
  # Code snippets
[Exeunt Romeo and Juliet]
```

These theatrical elements in SPL contribute to the unique and creative nature of the language. They serve not only as syntactic constructs but also as a way to infuse storytelling and drama into the act of programming.

## Incrementing and Reducting

Shakespeare Programming Language uses a unique syntax that is inspired by the style of William Shakespeare's plays. In ShakespeareLang, variables are represented by characters, and their values are manipulated through various dramatic actions.

1. **Increase Variable:**
   To increase a variable, you use the command "You are as [adjective]" where the adjective indicates something positive and the amount by which the variable should be increased. Here's an example:

   ```shakespeare
   Romeo, a young man with remarkable patience.
   Juliet, a woman with very little patience.

   [Enter Romeo and Juliet]

   Romeo: You are as sweet as the sum of yourself and a cat!
   ```
   In this example, the value of Juliet would be increased by the sum of the current value of herself and one.
  ###Or:

  ```
  Romeo: You sweet beautiful fair warm peaceful sunny summer's day!
  ```

  Both phrases increment Juliet's value.

1. **Decrease Variable:**
   To decrease a variable, you can follow the previous syntax, but use words considered as insults along with the keyword "difference". The number of insults indicates the amount by which the variable should be decreased. Here's two possible examples:

   ```shakespeare
   Romeo, a young man with remarkable patience.
   Juliet, a woman with very little patience.

   [Enter Romeo and Juliet]

   Juliet: You are as cowardly as the difference of yourself and a lying stupid pig.
   ```

   In this example, the value of Romeo would be decreased by 3. "Lying", "stupid" and "pig" are considered negative nouns and decrease 1 each.

Remember that ShakespeareLang is more about the dramatic structure and less about practical programming. The language is intentionally designed to be challenging and expressive, so writing even simple programs in it can be quite verbose and unconventional.

## Looping (with if-goto)

A sentence like ''Let us return to scene III'' means simply ''goto scene III''. Instead of ''let us'', you may use ''we shall'' or ''we must'', and instead of ''return to'', you may use ``proceed to''. If you specify a scene, it refers to that scene in the current act. There is no way to refer to a specific scene in another act - you have to settle for jumping to the act itself.

### Looping example:
```shakespeare
Juliet:
 Am I better than you?
Hamlet:
 If so, let us proceed to scene III.
```

Here, if the value of Juliet > Value of Hamlet, then the program goes to the start of the third scene. The use of acts and scenes is incredibly useful in situations where decisions on the looping or the general flow of the code need to be taken.

You can compare variables with words, to check for a specific value.

```shakespeare
Juliet: Am I better than a sunny beautiful day?
```

In this comparison, we are checking if Juliet's value is higher than the number 2. Day is a neutral word, considered +0.

## Setting values
In SPL, setting values for variables is a crucial aspect of programming, and it's expressed in a manner reminiscent of assigning roles or attributes to characters in a Shakespearean play. Let's explore how setting values is achieved in SPL.

### Setting Values:

Setting values involves assigning specific attributes or characteristics to variables (characters) within the script. In SPL, this process is dramatized to align with the language's Shakespearean inspiration.

#### Syntax:

```shakespeare
<VariableName>: Thou art the <Calculation> of <Value>.
```

#### Example:

```shakespeare
Romeo: Thou art the sum of a cat and the square of yourself.
```

In this example, the value associated with the variable Romeo is set to be the sum of a cat and the square of Romeo's current value.

### Combining Setting Values with Actions:

You can combine the act of setting values with character actions to create a more expressive and narrative style in your code.

#### Example:

```shakespeare
Romeo: Thou art the sum of a cat and the square of yourself.
Juliet: Speak thy mind.
```


## Calculations
In SPL, performing calculations takes on a theatrical and expressive form, aligning with the language's Shakespearean inspiration. The language allows you to script mathematical operations and expressions in a manner that reflects the dramatic nature of a play.

### Basic Arithmetic Calculations:

SPL supports basic arithmetic operations such as addition, subtraction, multiplication, and division. These operations are framed in a way that resembles characters interacting on a stage.

#### Syntax:

```shakespeare
<VariableName>: Thou art the sum/difference/square root of <Expression>.
```

#### Example:

```shakespeare
Romeo: Thou art the sum of Juliet and a cat.
Juliet: Thou art the product of Romeo and the square of yourself.
```

In these examples, the values associated with Romeo and Juliet are calculated based on the specified expressions.

### Sum and Difference:

Performing the sum or difference of variables in SPL is dramatized to resemble characters combining or contrasting their qualities on a theatrical stage.

#### Syntax:

```shakespeare
<VariableName>: Thou art the sum/difference of <Variable1> and <Variable2>.
```

#### Example:

```shakespeare
Romeo: Thou art the sum of Juliet and a cat.
Juliet: Thou art the difference between Romeo and a dog.
```

In these examples, Romeo's value is incremented by one and Juliet's decreases by one.

### Square Root:

Taking the square root of a variable is framed in a way that captures the essence of revealing hidden depths or uncovering secrets within the play.

#### Syntax:

```shakespeare
<VariableName>: Thou art the square root of <Variable>.
```

#### Example:

```shakespeare
Romeo: Thou art the square root of Juliet.
```

Here, the value associated with Juliet is set to be the square root of her value.

### Division:

Shakespeare Programming Language (SPL) does not have a native division operation. If you need to achieve division-like behavior in SPL, you would typically have to create a narrative or a sequence of events that mimics the desired mathematical operation. 

## Input and Output

In SPL, handling input and output is an integral part of the script, adding a dramatic dimension to the interaction between characters (variables) and the external world. The language employs a storytelling approach to depict the exchange of information within the program.

### Input:

Getting input in SPL is akin to characters receiving messages or cues from the audience. This can be used to set the stage for subsequent actions or decisions within the play. There are two types of input. **Character** and **Number**

#### Syntax for Number input:

```shakespeare
<VariableName>: Listen to your heart!
```

#### Example:

```shakespeare
Romeo: Listen to your heart!
```
#### Syntax for Character input:

```shakespeare
<VariableName>: Open up your mind!
```

#### Example:

```shakespeare
Romeo: Open up your mind!
```

In this example, the other character in the scene, Juliet, is instructed to listen to his heart, symbolizing the receipt of input.

### Output:

Outputting information in SPL is portrayed as characters expressing their thoughts, creating a dynamic and expressive form of communication.

#### Syntax:

```shakespeare
[Speak thy mind.]
```

#### Example:

```shakespeare
[Juliet: Speak thy mind.]
```

Here, the other character in the scene, Romeo, is prompted to speak his mind, representing the output of his value.

## Popping and Pushing in Characters' Stacks
In this programming language, each character is considered a stack. The concept of "remember thyself" could be implemented as a mechanism for variables (characters) to retain or recall their own values. This phrase adds a dramatic touch to the act of self-reference within the code.

### Pushing - *Remember Thyself*

In SPL, 'Remember thyself/yourself' allows to assign value to a character, by pushing that value into their 'stack'.

```shakespeare
[Enter Othello and Lady Macbeth]

Othello:
 You are nothing!

                    Scene II: Pushing to the very end.

Lady Macbeth:
 Open your mind! Remember yourself.
```

The last line specifically allows to read from the command line and assign the value to Othello, pushing it in the stack of values he has. Normally, as to how a stack behaves, the last value would be the one to be printed when 'popped'.

### Popping - *Speak Thy Value*

In Shakespeare Programming Language (SPL), you can use the phrase "Speak thy mind!" to instruct a character to reveal or speak their current thoughts or values. Here's an example:

```shakespeare
Scene I: The revelation.

[Enter Hamlet and Romeo]

Hamlet: Speak thy mind!
```

In this example, Romeo's value is printed on the screen.

-----
## References
- [@krayon](https://krayon.github.io/shakespearelang/docs/shakespeare.html)
- [Shakespearelang Official Site](https://shakespearelang.com/1.0/)

-----
## You can check code I've written, executed in an online SPL compiler:
- [x] <a href="https://tio.run/##pVPLrtMwEF03XzFZsanyAXeDrhCIIhASRUgIsZg4E2Jdexz50RJ@vowdF3JRu2LnxMfn5XGYzeXyeSJ4o3vHqJSGV2hUMhi147AHhNngApohnh2gigHihBGYaAgQnCXQdvbuRJY4dk3zSX65PTgmcKNgt9ScbE8@APJQdmZPJ@1SyOiueZeMprgvO4GUE9C/R7vm4zyR0biijHNzITuh19gbAjkVvTMmQz@g6ilOK/RJ8w9IURv9iwZA8QBhRkXlOIaCIVlWz5lZwjS73e5RRTg8wN2Suow6KpLAFXZgHTWKUtnPlAhvycxjMvClOpVT315zJA81UTFSLX9vrjkfGmF0CdDH7FIKi3FZ7feEkidzjqg9zCRp8ldIzAuc0VtZWkv@RYABlzYL/tTxr0bVLxf2TFEsEcPikoeJRLmVX1@zCdYWTXclqgcrzS3rRzH1tBJZzUNb@qxV1a6OMUerrb9fW7/tcx2P50Zvd1MGKNnMmrUDmbG0Wwy3t/JVyavE3Wa2er3HE13lBj2O5IlloMT0mYR/JauzvmQT7f80V1F3B2ITusqtow2TkwbaLfmjhQOwi9lqNiAPmv809XIrdRjlie/BSI6UxZySZw/RQaiXuN4WJZbWLpff" title="Shakespeare Programming Language – Try It Online">Fibonacci sequence in SPL</a>
 - [ ] Harmonic Sequence in SPL
