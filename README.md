wait(2)
local function callback(text)
    if text == "Yes" then
    print("User said yes")
    elseif text == "No" then
    print("User said no")
    end
end
 

 
local bindableFunction= Instance.new("BindableFunction")
 
game.StarterGui:SetCore("SendNotification", {
    Title = "AIMING";
    Text = "Emperyan.lua .gg/DFkRydn24R";
    Icon = "BLANK";
    Duration = "10";
    callbakc = bindableFunction;
    Button1 = "Okay";
})

loadstring(game:HttpGet("https://raw.githubusercontent.com/Horizon89002/Empyrean.lua/refs/heads/main/Empyreandh.lua"))()
