# PokeApi: tipos de imágenes de los Pokémones que puedes escoger para mostrar en tu app

El siguiente código es para Vue ✌🏽 pero puedes extraer en link del src y usarlo en cualquier framework 😊

## **Retro** 
uno de los más bonitos porque tiene ese toque pixeleado pero las imágenes son muy pequeñitas y agrandarlas les reduce calidad 😓

```ruby
<img :src="`https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/${getPokemonId(pokemon.url)}.png`" alt="pokemon.name" />
```
![image](https://github.com/user-attachments/assets/913d9c62-70ad-48ba-adc3-7ae7080eae66)

## **Home** 
se ven como en 3D
```ruby
<img :src="`https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/other/home/${getPokemonId(pokemon.url)}.png`" alt="pokemon.name" />
```
![image](https://github.com/user-attachments/assets/d48f878f-b930-4c75-a1d3-bd51a938e3b1)

## **Dream World Art**
se ven como dibujados
```ruby
 <img :src="`https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/other/dream-world/${getPokemonId(pokemon.url)}.svg`" alt="pokemon.name" />
```
![image](https://github.com/user-attachments/assets/5d32221b-4c15-495e-b53b-d3a4a2175fbe)


## **Other Art Work**
dibujos más naturales de los pokemones, de mejor calidad 🤗
```ruby
<img :src="`https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/other/official-artwork/${getPokemonId(pokemon.url)}.png`" alt="pokemon.name" />
```
![image](https://github.com/user-attachments/assets/3902d450-4da0-44e0-bb85-d0b223134639)
