
# PokeGOAPI-Java
Pokemon GO Java API
See this guide for adding functionality: https://docs.google.com/document/d/1BE8O6Z19sQ54T5T7QauXgA11GbL6D9vx9AAMCM5KlRA/edit
See this spreadsheet for RPC endpoints and progress: https://docs.google.com/spreadsheets/d/1Xv0Gw5PzIRaVou2xrl6r7qySrcmOKjQWLBjJA73YnJM/edit#gid=0

# Usage
Mostly everything is accessed through the PokemonGo class in the api package.
The constructor of PokemonGo class requires a AuthInfo object which can be obtained from GoogleLogin().login method (or others in future).

EG:
```java
AuthInfo auth = new GoogleLogin().login("token");           
PokemonGo go = new PokemonGo(auth);
System.out.println(go.getPlayerProfile());
```

## Contributing
1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Credits
Grover-c13

zeladada
