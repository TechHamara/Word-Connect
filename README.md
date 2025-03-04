# Word-Connect
Word Connection is a fun and engaging word puzzle game for app inventor

<div align="center">
<h1><kbd>🧩 WordConnect</kbd></h1>
An extension for MIT App Inventor 2.<br>
This component is developed by th using Fast.<br>Word Connection is a fun and engaging word puzzle game<br>where players link related words to form meaningful connections.<br>Challenge your vocabulary, improve your thinking skills,<br>and enjoy different game modes!<br>Word Connection is an addictive and educational word puzzle game that tests your vocabulary and logical thinking.<br>Players are given a set of words and must find meaningful connections between them.<br>Word Connection provides a fun way to expand your language skills and boost your brainpower.<br><a href='https://t.me/techhamara91/' target='_blank'>Telegram</a> | <a href='https://github.com/TechHamara/' target='_blank'>GitHub</a><br><a href='https://techhamara.blogspot.com/' target='_blank'>Blogger</a> | <a href='https://m.youtube.com/c/TECHHAMARA?sub_confirmation=1' target='_blank'>YouTube</a><br><a href='https://github.com/TechHamara/Th_Extensions_List/blob/main/LICENSE.md#terms-and-conditions-for-the-extension' target='_blank'><small><u>Terms & Conditions</u></small></a>
</div>

## 📝 Specifications
* **
📦 **Package:** io.th.wordconnect.wordconnect
💾 **Size:** 56.01 KB<br>
⚙️ **Version:** 1.0<br>
📱 **Minimum API Level:** 7<br>
📅 **Updated On:** [date=2025-03-03 timezone="Asia/Calcutta"]<br>
🔗 **Help URL:** [Learn more](https://github.com/TechHamara/Word-Connect)<br>
⚖️ **License:** [Terms & Conditions](https://github.com/TechHamara/Th_Extensions_List/blob/main/LICENSE)<br>
💻 **Built & documented using:** [FAST-CLI](https://community.appinventor.mit.edu/t/fast-an-efficient-way-to-build-extensions/129103?u=jewel) `v2.4.2`<br>

## <kbd>Events:</kbd>
**WordConnect** has total 11 events.

### 💛 PatternEntered
Pattern was entered by the user. Example: '12345'

| Parameter | Type
| - | - |
| pattern | text

### 💛 PatternAbandoned
Pattern input was abandoned

### 💛 AnimateInStarted
Animation to show pattern view has started

### 💛 AnimateInCompleted
Animation to show pattern view has completed

### 💛 AnimateOutStarted
Animation to hide pattern view has started

### 💛 AnimateOutCompleted
Animation to hide pattern view has completed

### 💛 PatternSizeChanged
Pattern size changed. Example: PatternSizeChanged(5) is triggered when the pattern size changes to 5.

| Parameter | Type
| - | - |
| newSize | number

### 💛 Error
Error occurred during pattern operation

| Parameter | Type
| - | - |
| errorMessage | text

### 💛 PatternSaved
Pattern was successfully saved. This event is triggered after a pattern has been successfully saved. Example: If a user sets a new pattern, this event will be triggered to indicate that the pattern has been saved successfully.

| Parameter | Type
| - | - |
| key | text

### 💛 PatternVerified
Pattern verification result. This event is triggered after attempting to verify a pattern. It returns a boolean indicating whether the pattern was successfully verified or not. Example: If the pattern entered by the user matches the saved pattern, this event will be triggered with 'matches' set to true.

| Parameter | Type
| - | - |
| key | text
| matches | boolean

### 💛 MaxAttemptsReached
Maximum attempts reached. Example: If the maximum attempts is set to 5 and the user has reached 5 attempts, this event will be triggered.

| Parameter | Type
| - | - |
| timeoutSeconds | number

## <kbd>Methods:</kbd>
**WordConnect** has total 32 methods.

### 💜 Initialize
Initialize the ConnectPatternView within a given HorizontalArrangement or VerticalArrangement.

| Parameter | Type
| - | - |
| arrangement | component

### 💜 SetBackgroundColorRGB
Set background color using RGB values

| Parameter | Type
| - | - |
| red | number
| green | number
| blue | number

### 💜 SetBackgroundColorARGB
Set background color using ARGB values (with alpha transparency)

| Parameter | Type
| - | - |
| alpha | number
| red | number
| green | number
| blue | number

### 💜 SetTransparentBackground
Set transparent background

### 💜 SetGradientBackground
Set gradient background. Example: SetGradientBackground(Color.RED, Color.BLUE, true)

| Parameter | Type
| - | - |
| startColor | number
| endColor | number
| isVertical | boolean

### 💜 AnimateIn
Animate the pattern view in

### 💜 AnimateOut
Animate the pattern view out

### 💜 SetTwelveCircles
Set to 12 circle pattern (3x4 grid)

### 💜 SetSixteenCircles
Set to 16 circle pattern (4x4 grid)

### 💜 SetEnabled
Set the pattern view enabled or disabled

| Parameter | Type
| - | - |
| enabled | boolean

### 💜 AnimateInWithDelay
Animate in with delay (in milliseconds)

| Parameter | Type
| - | - |
| delay | number

### 💜 AnimateOutWithDelay
Animate out with delay (in milliseconds)

| Parameter | Type
| - | - |
| delay | number

### 💜 CurrentPattern
Get current pattern as string. Example: CurrentPattern() returns '12345' for a pattern connecting points 1, 2, 3, 4, and 5.

### 💜 ResetToDefaults
Reset to default settings

### 💜 ValidPattern
Check if the current pattern is valid. Example: ValidPattern() returns true if the pattern has the minimum required points.

### 💜 CheckPattern
Check if the current pattern matches a specific pattern. Example: CheckPattern('123') checks if the current pattern matches '123'.

| Parameter | Type
| - | - |
| pattern | text

### 💜 PatternLength
Get the current pattern length. Example: PatternLength() returns the number of points in the current pattern.

### 💜 ValidPatternLength
Check if pattern meets minimum length requirement. Example: ValidPatternLength(5) checks if the current pattern length is at least 5.

| Parameter | Type
| - | - |
| minLength | number

### 💜 VerifyPattern
Load and verify a saved pattern. Example: VerifyPattern('patternKey') verifies the pattern saved under 'patternKey' and returns true if it matches the current pattern.

| Parameter | Type
| - | - |
| patternKey | text

### 💜 SetAttemptLimit
Sets the maximum number of attempts and timeout duration for pattern verification. Example: SetAttemptLimit(5, 60) sets the maximum attempts to 5 and timeout to 60 seconds.

| Parameter | Type
| - | - |
| maxAttempts | number
| timeoutSeconds | number

### 💜 RemainingAttempts
Get the number of remaining attempts before the timeout period expires. Example: If the maximum attempts is set to 5 and the user has made 3 attempts, this function will return 2, indicating 2 remaining attempts before the timeout period expires.

### 💜 ResetAttemptCounter
Reset pattern attempt counter. This function resets the counter for the number of attempts made to verify a pattern. Example: If the user has made 3 attempts to verify a pattern and wants to start fresh, this function can be called to reset the attempt count to 0.

### 💜 SavePattern
Save an encrypted pattern. Example: SavePattern('patternKey', 'patternString')

| Parameter | Type
| - | - |
| patternKey | text
| pattern | text

### 💜 SetLetters
Set letters for all dots. Use | to separate letters (e.g. 'A|B|C')

| Parameter | Type
| - | - |
| letters | text

### 💜 SetLetter
Set letter at a specific position (0-8)

| Parameter | Type
| - | - |
| position | number
| letter | text

### 💜 ShowParticles
Trigger success particle effect

### 💜 ShapeType
Set the shape of dots (circle, square, triangle, oval, pentagon, hexagon, star)

| Parameter | Type
| - | - |
| shapeName | text

### 💜 SetCircleShape
Set circle shape for dots

### 💜 SetSquareShape
Set square shape for dots

### 💜 SetTriangleShape
Set triangle shape for dots

### 💜 SetPentagonShape
Set pentagon shape for dots

### 💜 SetStarShape
Set star shape for dots

## <kbd>Setters:</kbd>
**WordConnect** has total 15 setter properties.

### 💚 CircleColor
Set the color of the circles

* Input type: `number`

### 💚 BackgroundColor
Set background color of the pattern view

* Input type: `number`

### 💚 BackgroundAlpha
Set background alpha (transparency) value (0-255)

* Input type: `number`

### 💚 NumberOfConnectors
Get current number of connectors

* Input type: `number`

### 💚 LineColor
Set the color of pattern lines

* Input type: `number`

### 💚 AnimationType
Set animation type (0 = None, 1 = Middle, 2 = Bottom)

* Input type: `number`

### 💚 CircleRadius
Set circle radius in dp

* Input type: `number`

### 💚 PatternVisible
Set pattern visibility

* Input type: `boolean`

### 💚 MinimumPatternLength
Set minimum required pattern length. Example: MinimumPatternLength(5) sets the minimum pattern length to 5.

* Input type: `number`

### 💚 ShowPatternLine
Enable/disable pattern visibility during drawing

* Input type: `boolean`

### 💚 LineWidth
Set the width of pattern lines

* Input type: `number`

### 💚 LetterColor
Set the color of letters

* Input type: `number`

### 💚 LetterSize
Set the size of letters in dp

* Input type: `number`

### 💚 ParticleColor
Set the color of success particles

* Input type: `number`

### 💚 Shape
Set the shape of dots (circle, square, triangle, oval, pentagon, hexagon, star)

* Input type: `text`
* Helper class: `Shape`
* Helper enums: `Circle`, `Square`, `Triangle`, `Ovel`, `Pentagon`, `Hexagon`, `Star`

## <kbd>Getters:</kbd>
**WordConnect** has total 11 getter properties.

### 🟢 CircleColor
Set the color of the circles

* Return type: `number`

### 🟢 White
Returns the color White

* Return type: `number`

### 🟢 Black
Returns the color Black

* Return type: `number`

### 🟢 Red
Returns the color Red

* Return type: `number`

### 🟢 Green
Returns the color Green

* Return type: `number`

### 🟢 Blue
Returns the color Blue

* Return type: `number`

### 🟢 Transparent
Returns a transparent color

* Return type: `number`

### 🟢 NumberOfConnectors
Get current number of connectors

* Return type: `number`

### 🟢 LineColor
Set the color of pattern lines

* Return type: `number`

### 🟢 AnimationType
Set animation type (0 = None, 1 = Middle, 2 = Bottom)

* Return type: `number`

### 🟢 LineWidth
Set the width of pattern lines

* Return type: `number`

