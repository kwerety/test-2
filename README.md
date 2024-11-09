# test-2
text 0
# text 1
## text 2
### text 3
#### text 4
##### text 5
###### text 6
![myphoto](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQJspELqK_DSc0f4vapC83KT0szMX4XX1r1xg&s)
```
body {
	background-image: url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTvI9U-ImGqO7fh6lVypwxZCbx0xSa-qLV_LA&s)
}

header {
	display: flex;
	justify-content: center;
}

.search.form {
	display: flex;
	justify-content: center;
	padding: 2rem 3rem;
	margin-top: 2rem;
	gap: 0.5rem;
	background-color: #fff;
	border: 3px solid #000;
	border-radius: 5rem; 
}

#search {
	color: #31AE9D;
	font-size: 2rem;
	border: none;
	outline: none;
	border-bottom: #000 3px solid;
}

#submit {
	width: 2rem;
	font-size: 2rem;
	background: none;
	border: none;
	cursor: pointer;
}

#search:valid, #search:focus {
	border-color: #31AE9D;
}

#submit:hover {
	animation: click .5s;
} 

@keyframes click {
	0% {
		transform: translateY(0);
	}
	50% {
		transform: translateX(3px);
	}
	100% {
		transform: translateY(0);
	}
}
```
