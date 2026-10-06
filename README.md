✈️ AERION-X Flying Car — Flight Simulator

AERION-X is an interactive browser-based 3D flying-car simulator built with HTML, CSS, JavaScript, and Three.js.

The simulator provides a virtual flight environment with VTOL flight, atmospheric cruise, landing simulation, cockpit view, pilot visualization, Earth, Moon, stars, flight telemetry, and manual controls.

Note: This is a virtual simulation/concept. It is not a real aircraft flight-control system and should not be used to design, build, or operate an actual aircraft or spacecraft.

🚀 Launch the Simulator

Open the live GitHub Pages version:

https://mdirfankhan2009.github.io/flying_car_3/

You can also run it locally by opening index.html through VS Code Live Server.

🎮 Flight Controls
Basic Controls
Key	Function
W	Increase throttle
S	Decrease throttle
↑	Pitch forward
↓	Pitch backward
A	Roll left
D	Roll right
Q	Yaw left
E	Yaw right
Space	Vertical thrust
R	Increase vertical thrust
F	Descend
C	Change camera
G	Deploy/retract landing gear
P	Toggle autopilot
X	Reset vehicle
🛸 Flight Modes

Use the number keys to change flight modes.

1 — VTOL Mode

VTOL stands for Vertical Take-Off and Landing.

Use this mode to take off from the landing pad.

Recommended sequence:

Press 1.

Increase throttle with W.

Hold Space to generate vertical thrust.

Watch the altitude indicator.

Once airborne, release Space.

Use ↑ to pitch forward.

Use A and D to control roll.

Use Q and E to control heading.

2 — Atmospheric Cruise

This mode simulates forward atmospheric flight.

Recommended controls:

W       Increase throttle
↑       Pitch forward
↓       Pitch backward
A / D   Roll
Q / E   Yaw


Build speed gradually and use small control inputs for smoother flight.

3 — Orbital Simulation

This mode provides a visual orbital-flight simulation with a different propulsion/acceleration model.

Use:

W       Increase simulated thrust
↑       Pitch
A / D   Roll
Q / E   Yaw
Space   Vertical thrust


The orbital mode is intentionally a simplified simulation. It does not represent a real spacecraft capable of reaching Low Earth Orbit.

A real LEO vehicle requires specialized propulsion, guidance, thermal protection, structural systems, staging/propellant systems, and atmospheric re-entry technology.

4 — Landing Mode

Landing mode is designed for practicing vertical landing.

Recommended procedure:

Press 4.

Reduce throttle using S.

Use F to descend.

Keep the vehicle approximately level using ↑, ↓, A, and D.

Deploy the landing gear with G.

Reduce vertical speed before reaching the ground.

Aim for the illuminated landing pad.

A soft landing requires keeping the vertical velocity low.

🎥 Camera Controls

Press C to cycle through the available cameras.

External Chase Camera

Provides a third-person view behind the vehicle.

Cockpit Camera

Places the camera inside the vehicle and shows the virtual pilot.

Overhead Camera

Provides a top-down view useful for landing and orientation.

📊 Flight Telemetry

The HUD displays:

Altitude

Air/vehicle speed

Vertical speed

Heading

Pitch

Roll

Throttle

Fuel

Flight-computer state

The telemetry is calculated from the simulator's current virtual flight state.

🤖 Autopilot

Press:

P


to toggle the simplified autopilot.

The autopilot assists with:

Attitude stabilization

VTOL hovering

Landing-mode descent

Throttle management

Autopilot is intended for simulation purposes only.

🛬 Landing Procedure

For a controlled landing:

1. Press 4
2. Press G to deploy landing gear
3. Reduce throttle with S
4. Use F to descend
5. Keep the vehicle level
6. Reduce vertical velocity
7. Touch down on the landing pad


If the vehicle becomes unstable, press:

X


to reset the simulation.

🖥️ Running Locally
Option 1 — VS Code

Install the Live Server extension.

Then:

Open the project folder in VS Code.

Open index.html.

Right-click the file.

Select Open with Live Server.

Option 2 — GitHub Pages

The project can be hosted as a static website using GitHub Pages.

The current deployment is:

https://mdirfankhan2009.github.io/flying_car_3/

🧩 Technology

The simulator uses:

HTML5

CSS3

JavaScript

Three.js

WebGL

GitHub Pages

Three.js provides the 3D rendering and scene management.

🌌 Simulation Features

Current virtual features include:

3D flying vehicle

VTOL simulation

Atmospheric flight simulation

Orbital simulation mode

Manual flight controls

Throttle control

Vertical thrust

Pitch control

Roll control

Yaw control

Gravity

Simplified drag

3D velocity

3D acceleration

Ground collision

Landing simulation

Landing gear

Cockpit

Virtual pilot

Engine effects

Earth

Moon

Star field

Landing pad

Flight telemetry

Autopilot

Multiple camera views

Flight reset

⚠️ Disclaimer

AERION-X is an experimental virtual flight simulation and visualization project.

The physics are simplified for browser-based simulation and entertainment. The simulated vehicle should not be interpreted as a validated aircraft, flying-car, rocket, spacecraft, or aviation design.

The orbital mode is especially simplified and does not model the complete physics or engineering requirements of an actual launch to Low Earth Orbit.

📜 License

This project can be modified and extended for educational, experimental, and visualization purposes according to the license included with this repository.
