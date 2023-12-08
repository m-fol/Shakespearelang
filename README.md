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
[Act <Act Number>: <Act Title>]
  # Code for the act goes here
[Exeunt]
```
Within each act, you have "scenes," which are smaller units of the program where specific actions or interactions take place. Scenes provide a way to organize the code further, allowing for a clear delineation of different stages within an act.
```shakespeare
[Scene <Scene Number>: <Scene Title>]
  # Code for the scene goes here
[Exeunt]
```
### Using Acts and Scenes Together:
Acts and scenes work together to create a structured and organized program. An act may contain multiple scenes, and each scene contributes to the overall narrative of that act. This structure helps make the code more readable, especially as the program grows in complexity.

Example:
```shakespeare
[Act 1: Initialization]
  [Scene 1: Variable Declarations]
    # Declare variables and initialize values
  [Exeunt]

  [Scene 2: Setup]
    # Additional setup code
  [Exeunt]
[Exeunt]

[Act 2: The Decision]
  [Scene 1: User Input]
    # Get input from the user
  [Exeunt]

  [Scene 2: Decision Making]
    # Perform logic based on user input
  [Exeunt]
[Exeunt]

```

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

Exiting a variable occurs when it is no longer needed in the program. This is similar to a character leaving the stage after their role in the play is complete. In programming terms, this may involve deallocating memory or releasing resources associated with the variable.

#### Syntax:

```shakespeare
[Exeunt <VariableName>]
```

#### Example:

```shakespeare
[Exeunt Romeo]
```

### "Exeunting" Variables:

The term "Exeunt" is borrowed from theatrical language, where it is used to signal the exit of characters from the stage. In SPL, "Exeunt" is used to signify the end of a block of code related to a specific variable. It encapsulates the actions or interactions involving that variable within a scene or act.

#### Syntax:

```shakespeare
[Exeunt]
```

#### Example:

```shakespeare
[Scene 1: Variable Declarations]
  Romeo, a young man with remarkable patience.
  Juliet, a young woman with an affinity for words.
[Exeunt]
```

In the above example, the use of "[Exeunt]" indicates the conclusion of the scene related to variable declarations. It adds a dramatic touch to the code, reminiscent of characters leaving the stage after their part in the play is performed.

These theatrical elements in SPL contribute to the unique and creative nature of the language. They serve not only as syntactic constructs but also as a way to infuse storytelling and drama into the act of programming.

## Incrementing and Reducting

In the Shakespeare-inspired programming language SPL, the concepts of "Incrementing" and "Reducing" are used to describe the increase and decrease of numerical values associated with variables, adding a theatrical and expressive touch to the typical programming operations.

### Incrementing:

Incrementing a variable in SPL is akin to a character gaining stature or increasing in value within the narrative. This operation is used when you want to increase the value of a numerical variable.

#### Syntax:

```shakespeare
[<VariableName>: Increase.]
```

#### Example:

```shakespeare
[Juliet: Increase.]
```

This syntax indicates that the value associated with the variable Juliet should be increased.

### Reducing:

Reducing, on the other hand, is the opposite of incrementing and signifies the decrease of a variable's value. In the dramatic context of SPL, this operation might represent a character losing importance or diminishing in some way.

#### Syntax:

```shakespeare
[<VariableName>: Decrease.]
```

#### Example:

```shakespeare
[Romeo: Decrease.]
```

In this example, the value associated with the variable Romeo would be decreased.

### Combining Incrementing and Reducing:

You can also combine incrementing and reducing operations to create more complex interactions and dramatic effects within your SPL code.

#### Example:

```shakespeare
[Juliet: Increase.]
[Romeo: Decrease.]
```

In this snippet, Juliet's value is increased, while Romeo's value is decreased, creating a dynamic relationship between the variables.

These theatrical and expressive elements in SPL make the act of manipulating variables more engaging and align with the Shakespearean inspiration of the language. The syntax choices aim to add a storytelling dimension to common programming operations, making the code both functional and entertaining.

## Looping (with if-goto)
In SPL, looping is achieved with a Shakespearean twist, and the concept of "If-Goto" is introduced to create conditional branching. This adds a theatrical flavor to the typical loop constructs found in traditional programming languages.

### Looping:

Looping in SPL involves characters (variables) engaging in a repetitive action until a certain condition is met. The characters follow a script of actions within a scene, creating a sense of continuity and rhythm in the code.

#### Syntax:

```shakespeare
[While <Condition>]
  # Code to be repeated while the condition is true
[End While]
```

#### Example:

```shakespeare
[Juliet: Speak thy mind.]
[While the Decision is hard]
  Juliet: Speak thy mind.
[End While]
```

In this example, Juliet speaks her mind initially, and then she continues to speak her mind while the decision is hard, creating a loop that repeats as long as the specified condition holds true.

### If-Goto for Conditional Branching:

To add conditional branching within loops, SPL employs an "If-Goto" structure. This is a departure from the traditional "If-Else" constructs and is more aligned with the theatrical and narrative style of Shakespearean plays.

#### Syntax:

```shakespeare
[If <Condition>]
  # Code to execute if the condition is true
[Else]
  # Code to execute if the condition is false
[End If]
```

#### Example:

```shakespeare
[While the Decision is hard]
  [If Juliet has spoken her mind]
    Juliet: Thou art brave!
  [Else]
    Juliet: Thou art a coward!
  [End If]
[End While]
```

In this example, the loop continues while the decision is hard. Within the loop, an If-Goto structure is used to check if Juliet has spoken her mind. If true, she is praised as brave; otherwise, she is labeled a coward.

By incorporating If-Goto into loops, SPL allows for dynamic and expressive control flow, giving the code a more narrative structure reminiscent of Shakespearean plays. This approach encourages programmers to think in terms of character actions and interactions, contributing to the unique and creative nature of the language.

## Setting values
In SPL, setting values for variables is a crucial aspect of programming, and it's expressed in a manner reminiscent of assigning roles or attributes to characters in a Shakespearean play. Let's explore how setting values is achieved in SPL.

### Setting Values:

Setting values involves assigning specific attributes or characteristics to variables (characters) within the script. In SPL, this process is dramatized to align with the language's Shakespearean inspiration.

#### Syntax:

```shakespeare
[<VariableName>: Thou art the <Value>.]
```

#### Example:

```shakespeare
[Romeo: Thou art the sum of a cat and the square of yourself.]
```

In this example, the value associated with the variable Romeo is set to be the sum of a cat and the square of Romeo's current value.

### Combining Setting Values with Actions:

You can combine the act of setting values with character actions to create a more expressive and narrative style in your code.

#### Example:

```shakespeare
[Romeo: Thou art the sum of a cat and the square of yourself.]
[Juliet: Speak thy mind.]
```

Here, Romeo's value is set, and Juliet speaks her mind in the same scene, creating a dynamic interaction between characters and setting the stage for further actions.

### Dynamic Setting of Values:

In SPL, you can dynamically set values based on the conditions or actions within the play, adding a layer of complexity to your code.

#### Example:

```shakespeare
[If Juliet has spoken her mind]
  [Romeo: Thou art the sum of a cat and the square of yourself.]
[Else]
  [Romeo: Thou art nothing.]
[End If]
```

In this snippet, the value assigned to Romeo depends on whether Juliet has spoken her mind or not. If she has, Romeo's value is set using a specific formula; otherwise, he is set to be nothing.

### Theatrical Setting of Values:

By adopting the Shakespearean style, SPL turns the mundane task of setting values into a theatrical performance, making the code both functional and entertaining. This approach encourages programmers to think in terms of character attributes and interactions, infusing creativity into the act of programming.

## Calculations
In SPL, performing calculations takes on a theatrical and expressive form, aligning with the language's Shakespearean inspiration. The language allows you to script mathematical operations and expressions in a manner that reflects the dramatic nature of a play.

### Basic Arithmetic Calculations:

SPL supports basic arithmetic operations such as addition, subtraction, multiplication, and division. These operations are framed in a way that resembles characters interacting on a stage.

#### Syntax:

```shakespeare
[<VariableName>: Thou art the sum/product/difference/quotient of <Expression>.]
```

#### Example:

```shakespeare
[Romeo: Thou art the sum of Juliet and a cat.]
[Juliet: Thou art the product of Romeo and the square of yourself.]
```

In these examples, the values associated with Romeo and Juliet are calculated based on the specified expressions.

### Conditional Calculations:

Calculations can be conditioned on certain events or conditions within the play, adding a layer of complexity and drama to the mathematical operations.

#### Example:

```shakespeare
[If the Decision is hard]
  [Romeo: Thou art the sum of Juliet and a cat.]
[Else]
  [Romeo: Thou art the difference between Juliet and a cat.]
[End If]
```

In this example, the value assigned to Romeo depends on whether the decision is hard or not.

### Looping and Calculations:

Calculations can be incorporated into loops, allowing for repeated mathematical operations within a scene or act.

#### Example:

```shakespeare
[While Juliet is speaking]
  [Romeo: Thou art the sum of Juliet and a cat.]
  [Juliet: Thou art the product of Romeo and the square of yourself.]
[End While]
```

Here, the values of Romeo and Juliet are recalculated while Juliet is speaking, creating a dynamic interaction between the characters and the mathematical expressions.

### Theatrical Expression of Calculations:

In SPL, every calculation is expressed theatrically, turning the act of computation into a performance. By adopting this creative approach, the language not only supports mathematical operations but also encourages programmers to think in terms of characters, scenes, and acts, making the code both functional and entertaining.

In SPL, mathematical operations such as sum, difference, square root, and division are expressed with a Shakespearean flair, integrating them seamlessly into the narrative structure of acts, scenes, and character interactions.

### Sum and Difference:

Performing the sum or difference of variables in SPL is dramatized to resemble characters combining or contrasting their qualities on a theatrical stage.

#### Syntax:

```shakespeare
[<VariableName>: Thou art the sum/difference of <Variable1> and <Variable2>.]
```

#### Example:

```shakespeare
[Romeo: Thou art the sum of Juliet and a cat.]
[Juliet: Thou art the difference between Romeo and a dog.]
```

In these examples, the values associated with Romeo and Juliet are calculated based on the sum and difference of other variables.

### Square Root:

Taking the square root of a variable is framed in a way that captures the essence of revealing hidden depths or uncovering secrets within the play.

#### Syntax:

```shakespeare
[<VariableName>: Thou art the square root of <Variable>.]
```

#### Example:

```shakespeare
[Romeo: Thou art the square root of Juliet.]
```

Here, the value associated with Romeo is set to be the square root of Juliet's value.

### Division:

Division in SPL is portrayed as characters sharing or separating from one another, creating a sense of connection or disconnection.

#### Syntax:

```shakespeare
[<VariableName>: Thou art the quotient of <Variable1> and <Variable2>.]
```

#### Example:

```shakespeare
[Romeo: Thou art the quotient of Juliet and a cat.]
```

In this example, the value associated with Romeo is set to be the quotient of Juliet and a cat.

### Incorporating into Acts and Scenes:

These mathematical operations can be seamlessly integrated into the acts and scenes of your SPL code, creating a script that not only performs calculations but also tells a dramatic story.

#### Example:

```shakespeare
[Act 1: Initialization]
  [Scene 1: Variable Declarations]
    Romeo, a young man with remarkable patience.
    Juliet, a young woman with an affinity for words.
  [Exeunt]

  [Scene 2: Calculations]
    [Romeo: Thou art the sum of Juliet and a cat.]
    [Juliet: Thou art the difference between Romeo and a dog.]
  [Exeunt]
[Exeunt]
```

This example demonstrates how mathematical operations can be a part of a larger narrative structure within the SPL code.

In SPL, these mathematical expressions become part of the dramatic performance, turning the act of computation into a compelling and entertaining show on the programming stage.

## Input and Output

In SPL, handling input and output is an integral part of the script, adding a dramatic dimension to the interaction between characters (variables) and the external world. The language employs a storytelling approach to depict the exchange of information within the program.

### Input:

Getting input in SPL is akin to characters receiving messages or cues from the audience. This can be used to set the stage for subsequent actions or decisions within the play.

#### Syntax:

```shakespeare
[<VariableName>: Listen to your heart!]
```

#### Example:

```shakespeare
[Romeo: Listen to your heart!]
```

In this example, the character Romeo is instructed to listen to his heart, symbolizing the receipt of input.

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

Here, Juliet is prompted to speak her mind, representing the output of information.

### Combining Input and Output:

In SPL, input and output can be combined to create dynamic interactions between characters and the external world.

#### Example:

```shakespeare
[Romeo: Listen to your heart!]
[Juliet: Speak thy mind.]
```

In this snippet, Romeo receives input by listening to his heart, and Juliet responds by speaking her mind, creating a dialogue within the play.

### Theatrical Presentation of Input/Output:

SPL emphasizes the theatrical presentation of input and output, turning the mundane task of receiving and providing information into a dramatic performance. By adopting this creative approach, the language not only supports standard I/O operations but also encourages programmers to think in terms of character interactions and the unfolding drama of the program.

### User-Driven Dramatic Flow:

SPL can be designed to create a user-driven dramatic flow, where the audience (user) influences the direction of the play by providing input.

#### Example:

```shakespeare
[Romeo: Listen to your heart!]
[If Juliet has spoken her mind]
  [Juliet: Speak thy mind.]
[Else]
  [Juliet: Keep thy silence.]
[End If]
```

Here, Romeo listens to his heart, and the subsequent actions of Juliet depend on whether she has spoken her mind, introducing an element of user interaction.

In SPL, the integration of input and output operations becomes a storytelling device, making the programming experience both functional and entertaining. The language's unique approach fosters creativity and encourages programmers to think in terms of characters, scenes, and acts.

## Pushing and Pulling in Characters' Stacks
In this programming language, each character is considered a stack. The concept of "remember thyself" could be implemented as a mechanism for variables (characters) to retain or recall their own values. This phrase adds a dramatic touch to the act of self-reference within the code.

### Pulling - *Remember Thyself*

To implement the "remember thyself" concept, a character (variable) would recall and store its current value for later use.

#### Syntax:

```shakespeare
[<VariableName>: Remember thyself.]
```

#### Example:

```shakespeare
[Romeo: Remember thyself.]
```

In this example, the character Romeo is instructed to remember his own value.

### Dynamic Self-Reference:

The concept of "remember thyself" becomes useful in scenarios where a character needs to recall its own state for future calculations or decisions.

#### Example:

```shakespeare
[Romeo: Remember thyself.]
[Juliet: Thou art the sum of Romeo and thy own value.]
```

In this snippet, Juliet calculates her value based on the sum of Romeo and her own remembered value.

### Conditional Self-Reference:

"Remember thyself" can also be used conditionally, adding a layer of complexity to the self-reference based on certain events or decisions within the play.

#### Example:

```shakespeare
[If Juliet has spoken her mind]
  [Juliet: Remember thyself.]
[Else]
  [Juliet: Thou art nothing.]
[End If]
```

Here, Juliet remembers herself only if she has spoken her mind; otherwise, she is set to be nothing.

### Theatrical Expression:

The use of "remember thyself" in SPL adds a dramatic and expressive element to self-reference within the code. It aligns with the Shakespearean inspiration of the language, turning the act of recalling one's own value into a theatrical performance.

### Act and Scene Structure:

The "remember thyself" concept can be seamlessly integrated into acts and scenes, contributing to the narrative structure of the program.

#### Example:

```shakespeare
[Act 1: Initialization]
  [Scene 1: Variable Declarations]
    Romeo, a young man with remarkable patience.
    Juliet, a young woman with an affinity for words.
  [Exeunt]

  [Scene 2: Self-Reference]
    [Romeo: Remember thyself.]
    [Juliet: Thou art the sum of Romeo and thy own value.]
  [Exeunt]
[Exeunt]
```

In this example, the act and scene structure provides a context for the self-reference operations, making the code more organized and expressive.

By incorporating "remember thyself" into SPL, the language not only supports self-reference but also infuses a creative and entertaining aspect into the act of programming. The syntax choices and narrative structure encourage programmers to think in terms of characters and their interactions, enhancing the overall storytelling experience within the code.

### Pushing - *Speak Thy Value*

In our fictional Shakespearean-inspired language, let's introduce a feature called "Speak Thy Value" for characters to dynamically express their values in a dramatic fashion.

### Syntax:

```shakespeare
[<CharacterName>: Speak thy value, for it is <NewValue>.]
```

### Example:

```shakespeare
[Juliet: Speak thy value, for it is the sum of Romeo and a cat.]
```

### Usage:

- **Dynamic Interaction:**
  
  ```shakespeare
  [Romeo: Speak thy value, for it is 42.]
  [Juliet: Speak thy value, for it is the square of Romeo.]
  ```

- **Conditional Setting:**
  
  ```shakespeare
  [If Juliet has spoken her mind]
    [Romeo: Speak thy value, for it is the sum of thy own value and a cat.]
  [Else]
    [Romeo: Speak thy value, for it is the difference between thy own value and a dog.]
  [End If]
  ```

### Act and Scene:

```shakespeare
[Act 1: Initialization]
  [Scene 1: Character Setup]
    [Juliet: Speak thy value, for it is 10.]
  [Exeunt]

  [Scene 2: Dynamic Interaction]
    [Romeo: Speak thy value, for it is the sum of Juliet and a cat.]
    [Juliet: Speak thy value, for it is the product of Romeo and thy own value.]
  [Exeunt]
[Exeunt]
```

Incorporating "Speak Thy Value" adds a theatrical element to variable assignments, turning the act of expressing and receiving values into an entertaining script. The concise syntax aligns with the Shakespearean inspiration of the language.

## You can check code I've written, executed in an online SPL compiler:
- [x] <a href="https://tio.run/##pVPLrtMwEF03XzFZsanyAXeDrhCIIhASRUgIsZg4E2Jdexz50RJ@vowdF3JRu2LnxMfn5XGYzeXyeSJ4o3vHqJSGV2hUMhi147AHhNngApohnh2gigHihBGYaAgQnCXQdvbuRJY4dk3zSX65PTgmcKNgt9ScbE8@APJQdmZPJ@1SyOiueZeMprgvO4GUE9C/R7vm4zyR0biijHNzITuh19gbAjkVvTMmQz@g6ilOK/RJ8w9IURv9iwZA8QBhRkXlOIaCIVlWz5lZwjS73e5RRTg8wN2Suow6KpLAFXZgHTWKUtnPlAhvycxjMvClOpVT315zJA81UTFSLX9vrjkfGmF0CdDH7FIKi3FZ7feEkidzjqg9zCRp8ldIzAuc0VtZWkv@RYABlzYL/tTxr0bVLxf2TFEsEcPikoeJRLmVX1@zCdYWTXclqgcrzS3rRzH1tBJZzUNb@qxV1a6OMUerrb9fW7/tcx2P50Zvd1MGKNnMmrUDmbG0Wwy3t/JVyavE3Wa2er3HE13lBj2O5IlloMT0mYR/JauzvmQT7f80V1F3B2ITusqtow2TkwbaLfmjhQOwi9lqNiAPmv809XIrdRjlie/BSI6UxZySZw/RQaiXuN4WJZbWLpff" title="Shakespeare Programming Language – Try It Online">Fibonacci sequence in SPL</a>
 - [ ] Harmonic Sequence in SPL
