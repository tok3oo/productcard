# productcard
## this my example of product card 
### my name is vladimir
**i am javascript developer,**
*there is example of my code written on js*
```javascript
class Pokemon {
    name = "Null";
    attack;
    hp;
    id;
    constructor(idPokemon) {
        this.id = idPokemon;
        const xhr = new XMLHttpRequest();
        xhr.open('GET', url + idPokemon);
        xhr.responseType = 'json';
        xhr.send();
        xhr.onload = () => {
            this.name = xhr.response.name;
            this.attack = xhr.response.height;
            this.hp = xhr.response.weight;
            this.createSelft(firstContainer);
            this.createSelft(secondContainer);
        }
    }
}
```
