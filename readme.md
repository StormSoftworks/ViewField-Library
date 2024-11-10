# How to initiate the main frame
```local testLib = Lib:CreateUI("yourLibName")```

# How to create tab
```local testTab = testLib:CreateTab("YourLibTab")```

# How to create an section
```local testSection1 = testTab:CreateSection('YourLibSection')```

# How to create an textbox
```local TextBox1 = testSection1:CreateTextBox('button')```

# How to create an on/off
```local Trig1 = testSection1:CreateTrigger('youronoff')```

# How to create an button
```local testButton1 = testSection1:CreateButton('TestButton', function() print("TestButton") end)```

# How to create an dropdown
```local Dropdown1 = testSection1:CreateDropdown('dropdownTest', function(v) print(v) end, "one", "two", "three")```
