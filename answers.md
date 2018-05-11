1. Select the element that contains the profile image: var image = document.querySelector('img')
	Change the src attribute so it points to a picture of your choosing instead: image.src = 'https://placebear.com/400/400'

2. select the element that contains the photo of the sky: element = document.querySelector("div.portfolio-image img")
	change the src attribute to another picture URL of your choosing: element.src = 'https://placebear.com/325/225'

3. Select the heading that says "Panda the Bear" and change it to your own name: heading = document.querySelector('h1')
	heading.innerText = 'panda the cat'

4. Select the heading that says "Employment" and change it to something else: element = document.querySelector('div.info-inner-container h3')
	element.innerText = 'unemployed'

5. Change the colour of each element using the highlight class: 
	highlightelements = document.querySelectorAll('.highlight')
	for (i = 0; i < highlightelements.length; i++) {
    highlightelements[i].style.color = 'red' }

6. 

