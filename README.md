# theory   DOM

<ol>
   <li>innerhtml and inner text me ye diffence hai ki inner html me <h1> ravi </h1>  code bde me likh kr return krega jbki inner text code ko same hi return krenga . code ko exexute nhi krega</li>
</ol>



//task 1: make show and hide card program

const button = document.getElementById('showHideButton');
const container = document.getElementsByClassName('container')[0];

button.addEventListener('click', () => {
    if(container.style.display  == 'block'){
        container.style.display = 'none';
    }
     else {
        container.style.display = 'block'
     }   
})
