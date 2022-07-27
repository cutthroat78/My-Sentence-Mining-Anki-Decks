# Template-Language-Anki-Deck

# Note Type Code
## Card 1: Target Language -> Source Language
### Front
```
<div style='font-size: 15px;'>{{Gender}}</div>
{{Target Language}}{{Target Language Audio}}
```
### Back
```
{{FrontSide}}
<hr id=answer>
{{Source Language}}
<br>
<i>{{Target Language Sentence}}{{Target Language Sentence Audio}}</i>
<div style='font-size: 15px;'>{{Source Language Sentence}}</div>
{{Image}}
```
## Card 2: Source Language -> Target Language
### Front
```
{{Source Language}}
```
### Back
```
{{FrontSide}}
<hr id=answer>
<div style='font-size: 15px;'>{{Gender}}</div>
{{Target Language}}{{Target Language Audio}}
<br>
<i>{{Target Language Sentence}}{{Target Language Sentence Audio}}</i>
<div style='font-size: 15px;'>{{Source Language Sentence}}</div>
{{Image}}
```
## Card 3: Target Language Sentence -> Source Language Sentence
### Front
```
{{Target Language Sentence}}{{Target Language Sentence Audio}}
```
### Back
```
{{FrontSide}}
<hr id=answer>
{{Source Language Sentence}}
```
## Card 4: Source Language Sentence -> Target Language Sentence
### Front
```
{{Source Language Sentence}}
```
### Back
```
{{FrontSide}}
<hr id=answer>
{{Target Language Sentence}}{{Target Language Sentence Audio}}
```
## Styling
```
.card {
  font-family: arial;
  font-size: 20px;
  text-align: center;
  color: black;
  background-color: white;
}
```
