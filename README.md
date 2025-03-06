# Word-Connect
Word Connect extension to create fun and engaging word puzzle game for app inventor

<div align="center">
<h1><kbd>🧩 WordConnect</kbd></h1>
An extension for MIT App Inventor 2.<br>
This component is developed by th using Fast.<br>Word Connection is a fun and engaging word puzzle game<br>where players link related words to form meaningful connections.<br>Challenge your vocabulary, improve your thinking skills,<br>and enjoy different game modes!<br>Word Connection is an addictive and educational word puzzle game that tests your vocabulary and logical thinking.<br>Players are given a set of words and must find meaningful connections between them.<br>Word Connection provides a fun way to expand your language skills and boost your brainpower.<br><a href='https://t.me/techhamara91/' target='_blank'>Telegram</a> | <a href='https://github.com/TechHamara/' target='_blank'>GitHub</a><br><a href='https://techhamara.blogspot.com/' target='_blank'>Blogger</a> | <a href='https://m.youtube.com/c/TECHHAMARA?sub_confirmation=1' target='_blank'>YouTube</a><br><a href='https://github.com/TechHamara/Th_Extensions_List/blob/main/LICENSE.md#terms-and-conditions-for-the-extension' target='_blank'><small><u>Terms & Conditions</u></small></a>
</div>

## 📝 Specifications
* **
📦 **Package:** io.th.wordconnect.wordconnect<br>
💾 **Size:** 56.01 KB<br>
⚙️ **Version:** 1.0<br>
📱 **Minimum API Level:** 7<br>
📅 **Updated On:** [date=2025-03-03 timezone="Asia/Calcutta"]<br>
🔗 **Help URL:** [Learn more](https://github.com/TechHamara/Word-Connect)<br>
⚖️ **License:** [Terms & Conditions](https://github.com/TechHamara/Th_Extensions_List/blob/main/LICENSE)<br>
💻 **Built & documented using:** [FAST-CLI](https://community.appinventor.mit.edu/t/fast-an-efficient-way-to-build-extensions/129103?u=jewel) `v2.4.2`<br>
<br>
**Paid** Price - 4💲 USD.
  **INR** UPI - 350rs.<br>
**Find** more Extension [here](https://github.com/TechHamara/Th_Free_Extensions)<br>
<br>
## Demo blocks
![Demo-blocks](https://github.com/user-attachments/assets/9b4d194c-7767-416a-a36a-2fb8a2929d82)

<br>


## <kbd>Events:</kbd>
**WordConnect** has total 11 events.


<br>


![PatternEnteredBlock](https://github.com/user-attachments/assets/719c5557-988a-44bd-bb42-d01f8053be32)
### 💛 PatternEntered
Pattern was entered by the user. Example: '12345'

| Parameter | Type
| - | - |
| pattern | text

![PatternAbandonedBlock](https://github.com/user-attachments/assets/4133ebdb-3ac3-4a2e-82f6-8e6609343d44)
### 💛 PatternAbandoned
Pattern input was abandoned

![AnimateInStartedBlock](https://github.com/user-attachments/assets/ca873484-3a92-4465-994b-c83d95162eee)
### 💛 AnimateInStarted
Animation to show pattern view has started

![AnimateInCompletedBlock](https://github.com/user-attachments/assets/7d5dfe21-893c-497f-a62e-c359a1640181)
### 💛 AnimateInCompleted
Animation to show pattern view has completed

![AnimateOutStartedBlock](https://github.com/user-attachments/assets/df268e36-cb56-4f29-9fdc-d1bd0ed99eb0)
### 💛 AnimateOutStarted
Animation to hide pattern view has started

![AnimateOutCompletedBlock](https://github.com/user-attachments/assets/24d0088e-2224-45a4-a93b-f9333839265b)
### 💛 AnimateOutCompleted
Animation to hide pattern view has completed

![PatternSizeChangedBlock](https://github.com/user-attachments/assets/f1712605-bc8f-4085-ba08-c274518f770b)
### 💛 PatternSizeChanged
Pattern size changed. Example: PatternSizeChanged(5) is triggered when the pattern size changes to 5.

| Parameter | Type
| - | - |
| newSize | number

![ErrorBlock](https://github.com/user-attachments/assets/7fb33ba9-b21c-49ac-8ba7-6faae812ee1d)
### 💛 Error
Error occurred during pattern operation

| Parameter | Type
| - | - |
| errorMessage | text

![PatternSavedBlock](https://github.com/user-attachments/assets/323c9578-504f-4229-8c84-654720686511)
### 💛 PatternSaved
Pattern was successfully saved. This event is triggered after a pattern has been successfully saved. Example: If a user sets a new pattern, this event will be triggered to indicate that the pattern has been saved successfully.

| Parameter | Type
| - | - |
| key | text

![PatternVerifiedBlock](https://github.com/user-attachments/assets/d0a6a222-f6b2-4981-b694-cd572f61766c)
### 💛 PatternVerified
Pattern verification result. This event is triggered after attempting to verify a pattern. It returns a boolean indicating whether the pattern was successfully verified or not. Example: If the pattern entered by the user matches the saved pattern, this event will be triggered with 'matches' set to true.

| Parameter | Type
| - | - |
| key | text
| matches | boolean

![MaxAttemptsReachedBlock](https://github.com/user-attachments/assets/2f9d3611-bc20-43e8-8568-b75b863c781c)
### 💛 MaxAttemptsReached
Maximum attempts reached. Example: If the maximum attempts is set to 5 and the user has reached 5 attempts, this event will be triggered.

| Parameter | Type
| - | - |
| timeoutSeconds | number


<br>


## <kbd>Methods:</kbd>
**WordConnect** has total 32 methods.

<br>

![InitializeBlock](https://github.com/user-attachments/assets/68625ed4-ed46-49a9-a555-3d3a5490fd7b)
### 💜 Initialize
Initialize the ConnectPatternView within a given HorizontalArrangement or VerticalArrangement.

| Parameter | Type
| - | - |
| arrangement | component

![BackgroundColorRGBBlock](https://github.com/user-attachments/assets/5dc0cb96-39b8-4263-aee5-7e868077f024)
### 💜 BackgroundColorRGB
Set background color using RGB values

| Parameter | Type
| - | - |
| red | number
| green | number
| blue | number

![BackgroundColorARGBBlock](https://github.com/user-attachments/assets/0d8ad4f9-651d-4616-aee9-73dae1de08a7)
### 💜 BackgroundColorARGB
Set background color using ARGB values (with alpha transparency)

| Parameter | Type
| - | - |
| alpha | number
| red | number
| green | number
| blue | number

![TransparentBackgroundBlock](https://github.com/user-attachments/assets/1ff76c23-22fa-4327-a6ad-307fb8b2644c)
### 💜 TransparentBackground
Set transparent background

![GradientBackgroundBlock](https://github.com/user-attachments/assets/5aa9e55a-5993-43d7-8e35-3ba520cf481e)
### 💜 GradientBackground
Set gradient background. Example: SetGradientBackground(Color.RED, Color.BLUE, true)

| Parameter | Type
| - | - |
| startColor | number
| endColor | number
| isVertical | boolean

![AnimateInBlock](https://github.com/user-attachments/assets/77484aeb-56ac-476d-8d78-f82dfa7066b3)
### 💜 AnimateIn
Animate the pattern view in

![AnimateOutBlock](https://github.com/user-attachments/assets/a30bd442-6709-496c-99b3-dd73b2891404)
### 💜 AnimateOut
Animate the pattern view out

![TwelveCirclesBlock](https://github.com/user-attachments/assets/a1e9fcbc-ad29-417b-9c44-a5c18110777d)
### 💜 TwelveCircles
Set to 12 circle pattern (3x4 grid)

![SixteenCirclesBlock](https://github.com/user-attachments/assets/7d2b069c-a384-4281-86fb-020999cdbe9a)
### 💜 SixteenCircles
Set to 16 circle pattern (4x4 grid)

![EnabledBlock](https://github.com/user-attachments/assets/d3be4716-c098-41ce-9658-ffd2787e5252)
### 💜 Enabled
Set the pattern view enabled or disabled

| Parameter | Type
| - | - |
| enabled | boolean

![AnimateInWithDelayBlock](https://github.com/user-attachments/assets/5d56b67c-5e63-44e2-bf6d-7fb8241f2c41)
### 💜 AnimateInWithDelay
Animate in with delay (in milliseconds)

| Parameter | Type
| - | - |
| delay | number

![AnimateOutWithDelayBlock](https://github.com/user-attachments/assets/b2749c32-0935-4a06-b826-dbb0a27a0d5d)
### 💜 AnimateOutWithDelay
Animate out with delay (in milliseconds)

| Parameter | Type
| - | - |
| delay | number

![CurrentPatternBlock](https://github.com/user-attachments/assets/a2890592-9a25-4df8-901c-502569efdd52)
### 💜 CurrentPattern
Get current pattern as string. Example: CurrentPattern() returns '12345' for a pattern connecting points 1, 2, 3, 4, and 5.

![ResetToDefaultsBlock](https://github.com/user-attachments/assets/95efddd8-0af9-4568-8099-8848edc94922)
### 💜 ResetToDefaults
Reset to default settings

![ValidPatternBlock](https://github.com/user-attachments/assets/7c753ddc-321a-40ad-bf08-8545dedd6d47)
### 💜 ValidPattern
Check if the current pattern is valid. Example: ValidPattern() returns true if the pattern has the minimum required points.

### 💜 CheckPattern
Check if the current pattern matches a specific pattern. Example: CheckPattern('123') checks if the current pattern matches '123'.

| Parameter | Type
| - | - |
| pattern | text

![PatternLengthBlock](https://github.com/user-attachments/assets/248b0a14-ec91-47d2-bbc0-c6bfb9b26091)
### 💜 PatternLength
Get the current pattern length. Example: PatternLength() returns the number of points in the current pattern.

![ValidPatternLengthBlock](https://github.com/user-attachments/assets/c7d6808f-5a3e-4c1a-8d5d-2ef4e02a0cd7)
### 💜 ValidPatternLength
Check if pattern meets minimum length requirement. Example: ValidPatternLength(5) checks if the current pattern length is at least 5.

| Parameter | Type
| - | - |
| minLength | number

![VerifyPatternBlock](https://github.com/user-attachments/assets/57a7cf6d-22bf-405a-beb1-40229e266649)
### 💜 VerifyPattern
Load and verify a saved pattern. Example: VerifyPattern('patternKey') verifies the pattern saved under 'patternKey' and returns true if it matches the current pattern.

| Parameter | Type
| - | - |
| patternKey | text

![AttemptLimitBlock](https://github.com/user-attachments/assets/83424ecc-240f-47bb-9b1b-7cf1b9bde519)
### 💜 AttemptLimit
Sets the maximum number of attempts and timeout duration for pattern verification. Example: SetAttemptLimit(5, 60) sets the maximum attempts to 5 and timeout to 60 seconds.

| Parameter | Type
| - | - |
| maxAttempts | number
| timeoutSeconds | number

![RemainingAttemptsBlock](https://github.com/user-attachments/assets/d1854750-8afe-491b-b7e8-cd6193b14335)
### 💜 RemainingAttempts
Get the number of remaining attempts before the timeout period expires. Example: If the maximum attempts is set to 5 and the user has made 3 attempts, this function will return 2, indicating 2 remaining attempts before the timeout period expires.

![ResetAttemptCounterBlock](https://github.com/user-attachments/assets/28616b43-38e2-43b3-b319-55107f3a5896)
### 💜 ResetAttemptCounter
Reset pattern attempt counter. This function resets the counter for the number of attempts made to verify a pattern. Example: If the user has made 3 attempts to verify a pattern and wants to start fresh, this function can be called to reset the attempt count to 0.

![SavePatternBlock](https://github.com/user-attachments/assets/bc9a1f85-4dec-433c-89bf-7f05b9ab40a4)
### 💜 SavePattern
Save an encrypted pattern. Example: SavePattern('patternKey', 'patternString')

| Parameter | Type
| - | - |
| patternKey | text
| pattern | text

![LettersBlock](https://github.com/user-attachments/assets/142ff55d-ee2a-44cd-b30a-cb3ad9aacee4)
### 💜 Letters
Set letters for all dots. Use | to separate letters (e.g. 'A|B|C')

| Parameter | Type
| - | - |
| letters | text

![LetterBlock](https://github.com/user-attachments/assets/850e1d39-8b98-4e42-a360-ebd916c321cd)
### 💜 Letter
Set letter at a specific position (0-8)

| Parameter | Type
| - | - |
| position | number
| letter | text

![ShowParticlesBlock](https://github.com/user-attachments/assets/7d7ceffd-7919-4926-8983-27c072e90577)
### 💜 ShowParticles
Trigger success particle effect

![ShapeTypeBlock](https://github.com/user-attachments/assets/10cd3de3-b2eb-443f-ae89-a27e161a05a0)
### 💜 ShapeType
Set the shape of dots (circle, square, triangle, oval, pentagon, hexagon, star)

| Parameter | Type
| - | - |
| shapeName | any

![CircleShapeBlock](https://github.com/user-attachments/assets/2caba6c0-9208-4ca7-b910-74c09bafc194)
### 💜 CircleShape
Set circle shape for dots

![SquareShapeBlock](https://github.com/user-attachments/assets/49242599-f160-4689-89da-332e04ef37a7)
### 💜 SquareShape
Set square shape for dots

![TriangleShapeBlock](https://github.com/user-attachments/assets/6e60b99c-bffd-4886-8783-2ecae5aac238)
### 💜 TriangleShape
Set triangle shape for dots

![PentagonShapeBlock](https://github.com/user-attachments/assets/c0509ff5-a662-4fc9-baa5-396abf9bc3e7)
### 💜 PentagonShape
Set pentagon shape for dots

![StarShapeBlock](https://github.com/user-attachments/assets/cebe5422-ae83-4303-b8c2-6bddc6d4a7b0)
### 💜 StarShape
Set star shape for dots

![OvalShapeBlock](https://github.com/user-attachments/assets/992ed438-7470-4205-96bb-6ca12205e6d5)
### 💜 OvalShape
Set oval shape for dots

![HexagonShapeBlock](https://github.com/user-attachments/assets/db63886c-2ddf-4320-bc6c-5205b3048562)
### 💜 HexagonShape
Set hexagon shape for dots

![StarShapeBlock](https://github.com/user-attachments/assets/e9d01098-5df0-493c-8e1e-65ad80bab616)
### 💜 StarShape
Set star shape for dots

<br>

## <kbd>Setters:</kbd>
**WordConnect** has total 15 setter properties.

<br>

![CircleColorBlock](https://github.com/user-attachments/assets/b1baaab8-529d-4d4e-9edc-e55fb93c1f07)
### 💚 CircleColor
Set the color of the circles

* Input type: `number`

![BackgroundColorBlock](https://github.com/user-attachments/assets/ee22ebe2-e2cf-44c7-9aa5-2fa6279a31a4)
### 💚 BackgroundColor
Set background color of the pattern view

* Input type: `number`

![BackgroundAlphaBlock](https://github.com/user-attachments/assets/0d7c5a78-0a3e-44d8-948a-c5d766707131)
### 💚 BackgroundAlpha
Set background alpha (transparency) value (0-255)

* Input type: `number`

![NumberOfConnectorsBlock](https://github.com/user-attachments/assets/d4b55326-b4d9-4c80-919e-c2b59f651b4e)
### 💚 NumberOfConnectors
Get current number of connectors

* Input type: `number`

![LineColorBlock](https://github.com/user-attachments/assets/98e0b7a6-56cf-4b61-afba-03cee7a73939)
### 💚 LineColor
Set the color of pattern lines

* Input type: `number`

![AnimationTypeBlock](https://github.com/user-attachments/assets/5c678693-dd26-4077-9f0c-bd0afb4b0a1a)
### 💚 AnimationType
Set animation type (0 = None, 1 = Middle, 2 = Bottom)

* Input type: `number`

![CircleRadiusBlock](https://github.com/user-attachments/assets/33245879-17af-4768-ba6c-4184bd6bd6d3)
### 💚 CircleRadius
Set circle radius in dp

* Input type: `number`

![PatternVisibleBlock](https://github.com/user-attachments/assets/42d49e41-b297-48e3-90f7-a546926a5ccd)
### 💚 PatternVisible
Set pattern visibility

* Input type: `boolean`
* 
![MinimumPatternLengthBlock](https://github.com/user-attachments/assets/9022cfbb-d53e-40bf-b041-14addb54f547)
### 💚 MinimumPatternLength
Set minimum required pattern length. Example: MinimumPatternLength(5) sets the minimum pattern length to 5.

* Input type: `number`

![ShowPatternLineBlock](https://github.com/user-attachments/assets/751106c4-4681-461d-8d65-88ff24b52b34)
### 💚 ShowPatternLine
Enable/disable pattern visibility during drawing

* Input type: `boolean`

![LineWidthBlock](https://github.com/user-attachments/assets/87cf3fbe-9dbc-4353-86a3-87631048e968)
### 💚 LineWidth
Set the width of pattern lines

* Input type: `number`

![LetterColorBlock](https://github.com/user-attachments/assets/d7944c71-f86b-4401-9266-f2d71695c907)
### 💚 LetterColor
Set the color of letters

* Input type: `number`
* 
![LetterSizeBlock](https://github.com/user-attachments/assets/08579dcf-77ea-4312-b951-53d22a7ee48b)
### 💚 LetterSize
Set the size of letters in dp

* Input type: `number`

![ParticleColorBlock](https://github.com/user-attachments/assets/4ba8e119-797e-4419-9b72-eab704b68c93)
### 💚 ParticleColor
Set the color of success particles

* Input type: `number`

![ShapeBlock](https://github.com/user-attachments/assets/16faad19-43d2-4ada-945b-db0cdf5b1098)
### 💚 Shape
Set the shape of dots (circle, square, triangle, oval, pentagon, hexagon, star)

* Input type: `any`
* Helper class: `Shape`
* Helper enums: `Circle`, `Square`, `Triangle`, `Ovel`, `Pentagon`, `Hexagon`, `Star`

<br>

## <kbd>Getters:</kbd>
**WordConnect** has total 11 getter properties.

<br>

<img width="256" alt="CircleColor" src="https://github.com/user-attachments/assets/06011fdb-1a88-4994-b48e-470b5a26c0b5" />

### 🟢 CircleColor
Set the color of the circles

* Return type: `number`

![WhiteBlock](https://github.com/user-attachments/assets/054e94bc-de0f-40f6-a366-f3abe5bab8c4)
### 🟢 White
Returns the color White

* Return type: `number`

![BlackBlock](https://github.com/user-attachments/assets/a397af07-0793-4c6a-91d5-e183f17685b3)
### 🟢 Black
Returns the color Black

* Return type: `number`

![RedBlock](https://github.com/user-attachments/assets/3fc0c175-1f7b-40b4-9ec9-73bee43a2d6c)
### 🟢 Red
Returns the color Red

* Return type: `number`

![GreenBlock](https://github.com/user-attachments/assets/80b65ce8-687e-4cc6-93d2-1b91672ed0d7)
### 🟢 Green
Returns the color Green

* Return type: `number`
* 
![BlueBlock](https://github.com/user-attachments/assets/f2fb4168-ad30-4ab7-9819-78975e11e19e)
### 🟢 Blue
Returns the color Blue

* Return type: `number`

![TransparentBlock](https://github.com/user-attachments/assets/467a7745-af75-4e37-a1e1-f8de8d08ac19)
### 🟢 Transparent
Returns a transparent color

* Return type: `number`

<img width="326" alt="NumberOfConnectors" src="https://github.com/user-attachments/assets/40d3c9fe-e9cd-463f-a5bd-b09cc5f5e3c6" />

### 🟢 NumberOfConnectors
Get current number of connectors

* Return type: `number`

<img width="246" alt="LineColor" src="https://github.com/user-attachments/assets/88fa1b3d-16e4-426d-9649-3ecf6fc37343" />

### 🟢 LineColor
Set the color of pattern lines

* Return type: `number`

<img width="280" alt="AnimationType" src="https://github.com/user-attachments/assets/3975183c-523a-4c2b-a127-b1c5838eb5e9" />

### 🟢 AnimationType
Set animation type (0 = None, 1 = Middle, 2 = Bottom)

* Return type: `number`

<img width="248" alt="LineWidth" src="https://github.com/user-attachments/assets/1d5920df-3ef8-4baa-b0ad-2369ebb166ad" />

### 🟢 LineWidth
Set the width of pattern lines

* Return type: `number`

![LettersBlock](https://github.com/user-attachments/assets/1fc11d82-4c5b-4561-b770-3b254458e80c)
### 🟢 Letters
Get the current letters as a string (separated by '|')

* Return type: `text`

![ShapeBlock](https://github.com/user-attachments/assets/a87818ec-6f36-4f1a-b369-7600e8b53efe)
### 🟢 Shape
Set the shape of dots

* Return type: `text`

  <br>

## <kbd>Helper:</kbd>
**WordConnect** has total 7 Helpers properties.

<br>

![CIRCLEBlock](https://github.com/user-attachments/assets/646e5b3a-8100-4148-83d2-f28d1ace8149)
### CIRCLE
Option for CIRCLE

* Returns: CIRCLE<br>
Deprecated: `false`

![SQUAREBlock](https://github.com/user-attachments/assets/332b8791-229a-4c24-b762-469d6fe8f170)
###  SQUARE
Option for SQUARE

* Returns: SQUARE<br>
Deprecated: `false`

![TRIANGLEBlock](https://github.com/user-attachments/assets/949dd88e-604a-45b8-ac48-8ded63b0789a)
###  TRIANGLE
Option for TRIANGLE

* Returns: TRIANGLE<br>
Deprecated: `false`

![OVALBlock](https://github.com/user-attachments/assets/de625acf-5c4d-4db1-8412-5eb40fdb0555)
###  OVAL
Option for OVAL

* Returns: OVAL<br>
Deprecated: `false`

![PENTAGONBlock](https://github.com/user-attachments/assets/d0ab64cf-1286-48a3-860d-d6cd3623b58c)
###  PENTAGON
Option for PENTAGON

* Returns: PENTAGON<br>
Deprecated: `false`

![HEXAGONBlock](https://github.com/user-attachments/assets/fa1a523b-f1b3-446b-b2cc-4b80b2548728)
###  HEXAGON
Option for HEXAGON

* Returns: HEXAGON<br>
Deprecated: `false`

![STARBlock](https://github.com/user-attachments/assets/43869c5e-53ea-45e2-9ffe-c7b5501e541d)
###  STAR
Option for STAR

* Returns: STAR<br>
Deprecated: `false`

## Thanks
   TechHamara

   
