local library = loadstring(game:HttpGet('https://raw.githubusercontent.com/luckyontop9/YesThisCool/main/NoobUiLib'))() local gg = library:Window("noob")

gg:Button("Button name", function() print("pressed button") end)

gg:Toggle("Example toggle", true, function(bool) print(bool) -- bool is true or false depending on the state of the toggle end)

gg:ColorPicker("Color Picker", Color3.fromRGB(255, 255, 255), function(color) print(color) end)

gg:Slider("Example Slider",0,100,20, function(value) print(value) end)

gg:Label("21", Color3.fromRGB(127, 143, 166))

gg:Box("Walkspeed", function(text, focuslost) if focuslost then print(text) end end)

local dropdown = OwO:Dropdown("Example dropdown", {"Button 1", "Button 2", "Third button"}, function(name) print(name) end)

dropdown:Button("New button")

dropdown:Remove("Button")
