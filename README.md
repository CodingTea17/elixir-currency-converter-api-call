# CurrencyConverterApiCall

This little project makes use of the HTTPoison library to get the current exchange rates from Euro -> USD. It's my first project using Elixir to make an API call. 

## Installation

1. Execute `mix deps.get` to install deps
2. Test by running `mix run -e "CurrencyConverterApiCall.from_euro_to_dollar(15) |> IO.puts"`
