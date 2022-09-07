# Durks Lib - Alpha Docs

# Starting the library

```lua
local lib = loadstring(game:HttpGet("https://raw.githubusercontent.com/idonthaveoneatm/Libraries/normal/DurksLib/Library.lua", true))()
```


# Creating a Window

```lua
local ui = lib:CreateUI("test", true)
```

# Creating a Tab

```lua
local w1 = ui:CreateWindow("Atest1")
```

# Creating a Container Max 2

```lua
local c1 = w1:CreateContainer("container1")
--[[local c2 = w1:CreateContainer("container2")]]--
```

# Creating a Button

```lua
local button1 = c1:CreateButton(function()
	print("hello world!")
end)

```

# Creating a Toggle

```lua
local toggle1 = c1:CreateToggle({
	Name = "Toggleyo",
	Default = true,
	CallBack = function(value)
		print(value)
	end
})
```

# Creating a Slider

```lua
local slider1 = c1:CreateSlider({
	Name = "slideryo",
	Min = 10,
	Max = 46,
	CallBack = function(value)
		print(value)
	end,
})
```

# to change a container on something change c1 to c2
