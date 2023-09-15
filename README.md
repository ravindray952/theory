# theory   DOM

<ol>
   <li>innerhtml and inner text me ye diffence hai ki inner html me <h1> ravi </h1>  code bde me likh kr return krega jbki inner text code ko same hi return krenga . code ko exexute nhi krega</li>
</ol>



//task 1: make show and hide card program
     //hide ho jayega button click krne pr nhi ayega 





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

 <h5>dom</h5>

//task 1: make show and hide card program

const button = document.getElementById('showHideButton');
const container = document.getElementsByClassName('container')[0];
 
function showHideCard(){
    if(container.style.display  == 'block'){
        container.style.display = 'none';
        button.innerText =  'Show Card'
        button.style.backgroundColor = 'green';
    }
     else {
        container.style.display = 'block'
        button.innerText = 'Hide Card';
        button.style.backgroundColor = 'grey';

     }   
}
button.addEventListener('click', () => showHideCard())

<h1>hide div by myself</h1> <br> <br/>

const container = document.getElementsByClassName("container")[0];
const button = document.getElementById("showHideButton")
const  heading = document.getElementsByClassName("heading1")
const allPara = document.getElementsByTagName("p")
const para = document.getElementById("para")


button.addEventListener('click', ()=>{
     container.style.display = 'none'
    console.log("click the button ")
});
