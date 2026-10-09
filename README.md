Shader 1: Reflections

My reflection shader uses a cubemap of the sky that I found online, using the view direction and normal vector.
I then Multiplied that together with the base texture and the base color. This differs from the in class model because 
I plugged it into the base color instead of pluggin it into the emission.
<img width="1041" height="562" alt="Car_Fragment" src="https://github.com/user-attachments/assets/9256b81c-a146-4204-8820-c4907c62f817" />


I also made it differ by adding a vertex shader the makes the car sway up and down simular to how cars bounce on the road.
I did this by moving the Z axis with the absolute value of a sin wave. Using the absolute value so it does not go underground.
<img width="940" height="322" alt="Car_Vertex" src="https://github.com/user-attachments/assets/b017497f-44c6-4fd7-8dfb-2a280e041e20" />

Shader 2: Moving Sand

I took a tiling node from the shader graph and multiplied it by time.
I also added a variable so you can change the speed of the tiling, making it look the the car is going faster or slower.
I didn't know about the tiling node before today but I was curious and looked up tiling in the node search on unity.
Interesting to learn that it plugs into UV because that was an alternate way to do what's in my next shader.
I also reused this shader for the sidewalls so that they scroll too.
<img width="951" height="397" alt="Sand_Fragment" src="https://github.com/user-attachments/assets/018bdc96-2aba-4644-ac65-89cfb956b56b" />

Shader 3: Using multiple UVs for smoke
The smoke shader is built off an idea I came up with last night.
I went into bender and make a subdivived cube. 
I then made UV0 be the default UVs and UV1 the same UVs but offset by 1.
What this does is creat 2 identical UVs in different positions.
Then in Unity I lerped between the two UVs in order to effectively slide the texture in a looping manor.
The resualt is very simular to the previous shader but with a very different way of getting there.
<img width="977" height="560" alt="Smoke_Fragement" src="https://github.com/user-attachments/assets/d5c53c5d-c033-4bc0-afdb-ae5272d627be" />

Shader 4: Lighting
N/A due to time 





