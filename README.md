# Library UI - ReactJS
It's a simple library with basic elements HTML :)

#Storybook


# Installation
```bash
npm i  dp-reactjs.ui
```
# Button
```javascript
<ButtonSimple
	backgroundColor="#000"
	color="#fff"
	fontFamily="Georgia"
	fontSize="14px"
	handleClick={() => {}}
	text="Test Texto"
/>
```
# Card
```javascript
<CardSimple
	backgroundColor="#fff"
	borderColor="#ccc"
	boxShadow="0 0 10px #719ECE"
	color="#000"
	foot="Test Food"
	title="Test T’tulo"
	width="100%"
>
	<h1>
		Test
	</h1>
</CardSimple>
```
# Dropdown
```javascript
<Dropdown
  backgroundColor="#ccc"
  colorBtn="#fff"
  colorContent="#cecece"
  colorHover="#dedede"
  colorLink="#000"
  fontFamily="Times New Roman"
  fontSize="20px"
  hoverLink="#333"
  items={[
    'Test 1',
    'Test 2'
  ]}
  links={[
    'https://www.google.com.mx',
    'https://www.twitter.com'
  ]}
  minWidth="150px"
  padding="10px 20px"
  targets={[
    '_blank',
    '_self'
  ]}
  title="Test Title"
/>
```
# Form 
```javascript
<FormSimple
  backgroundColor="#fff"
  borderColor="#000"
  btnBackgroundColor="#000"
  btnColor="#fff"
  btnFontFamily="Arial"
  btnFontSize="12px"
  btnText="Test Button"
  color="#000"
  handleSubmit={() => {}}
  title="Test Form"
  width="100%"
>
  <label>
    Nombre
  </label>
  <br />
  <input />
</FormSimple>
```
# Input
```javascript
<InputSimple
  backgroundColor="#fff"
  borderColor="#eee"
  color="black"
  focus="0 0 10px #719ECE"
  handleChange={() => {}}
  name="testName"
  placeholder="Test Placeholder"
  type="password"
/>
```
# Navbar
```javascript
<NavBar
  backgroundColor="#F18181"
  color="#fff"
  colorActive="rgba(209,204,204,1)"
  colorHover="rgba(250,10,10,0.54)"
  fontFamily="Times New Roman"
  fontSize="20px"
  items={[
    'Test 1',
    'Test 2',
    'Test 3'
  ]}
  links={[
    'https://www.google.com.mx',
    'https://www.twitter.com',
    'https://www.uaemex.mx'
  ]}
  padding="10px 15px"
  targets={[
    '_blank',
    '_blank',
    '_blank'
  ]}
/>
```
# ISC
2020 - developeralta
