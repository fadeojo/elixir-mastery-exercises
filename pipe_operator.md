# Use this code and data to answer the questions.

```elixir
defmodule Millenium.Falcon do
  def rebel?(c = %{rebel: true}) do
    c.type != :droid
  end

  def rebel?(_), do: false

  def fill_ship(characters) do
    characters
    |> Enum.map(&(&1.name))
    |> Enum.join(",")
  end
end

characters = [
  %{name: "Han",        type: :human,   rebel: true,    weight: 185},
  %{name: "Jabba",      type: :hutt,    rebel: false,   weight: 2200},
  %{name: "Chewie",     type: :wookie,  rebel: true,    weight: 350},
  %{name: "r2d2",       type: :droid,   rebel: true,    weight: 250},
  %{name: "Luke",       type: :human,   rebel: true,    weight: 140},
  %{name: "Boba Fett",  type: :human,   rebel: false,   weight: 175},
]

```

## Exercise 1

* Create a list of all the rebel scum

## Exercise 2

* Fill the Millenium Falcon with all the rebels

## Exercise 3

* How much do all the humans weigh?

## Exercise 4 (BONUS)

* If the Millenium Falcon can hold 1000 pounds, what is the optimal set of characters that can fit on the ship without going over the weight limit?


[Answer](https://gist.github.com/brweber2/5d594842ac81d55d92ee6b44510bfc45)
