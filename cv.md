Kolya Konoplich
My mail: kolikamatan@gmail.com
My telegram: https://t.me/ph1zpunk
My Discord: физмаятник#5994
I aspire to become a top front-end developer, I'm extremely interested in helping to implement someone's interesting ideas, and implement my own.
I'm proficient in HTML, CSS and JavaScript, I'm also good at git and have worked with AWS.
//my code for sending data via ajax request, and checking it for correctness
document.querySelector('#submit').onclick = function(event){
    event.preventDefault();
    console.log('work');
    let name = document.querySelector('#name').value;
    let surname = document.querySelector('#surname').value;
    let email = document.querySelector('#email').value;
    let number = document.querySelector('#number').value;
    let messages = document.querySelector('#messages').value;
  
    let data = {
       "name" : name,
       "surname" : surname,
       "email" : email,
       "number" : number,
       "messages" : messages,
    
}
    ajax('thanks.html', 'GET', login, data);
    function login(result){
        console.log(result);
        if (result == 2){
            alert('Заполните поля');
        } else if (result == 1){
            alert('Успех!')
        }
        else{
            alert('Ошибка, повторите регистрацию позже!')
        }
    }
    document.form.reset();
} 
I am Junior Dev
I speak English at a basic level