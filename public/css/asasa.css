const cityName = document.getElementById('cityName');
const submitBtn = document.getElementById('submitBtn');

const city_name = document.getElementById('city_name');


const getInfo = async(event) =>{
    event.preventDefault();
    let cityVal = cityName.value; 
    if(cityVal === ""){
        city_name.innerText = `Plz write the name before search`;
    }else{
        try{
            let url = `api.openweathermap.org/data/2.5/weather?q=${cityVal}&appid=c55c45d990d311fc1ce91c582f6ea7b8`;
            const response = await fetch(url);
           }catch{
            city_name.innerText = `Plz enter the city name properly`; 
            datahide.classList.add('data_hide');
        } 
    }

}

submitBtn.addEventListener('click', getInfo);        