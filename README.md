# Rocket-Diesel-Blog
## Launching APIs in [Rocket](https://rocket.rs) with [Diesel](https://diesel.rs) as fuel and [Rust](https://www.rust-lang.org/) as Pilot

> We are going to launch this Rocket to Moon 


1. ### The blueprint (It should be Pointy)
   * Collect all Tools (Setup, Linting and Editor setting)
   * Where's the diagram 
2. ### Build the Chassis and Engine
   * Setup the workshop (Setup the environment)
   * Create the frame (Application folder structure) 
3. ### Build the control
   * Create Switch to give current status
   * Create switch to turn solar panels
   * Create Joystick to rotate the rocket control the thruster
   * Release Parachute
   * Create a schedule to rotate around moon for 10mins and take some photos of the surface
4. ### Build the connection with Control Tower (CT)
    * Control how we use the Fuel (Diesel)
    * Let's make sure CT can track the trajectory for our Rocket (Diesel connection)
    * Let's make sure we have a persistant connection with our Rocket (Connection state)
    * Find a way to send new instructions to Rocket on the fly (Migrations)
5. ### Securing Connection with Spaceship and CT
     * Adding security 
6. ### Houston we have a problem
    * What to do in case we see aliens (In appropriate payload and data)
    * Can we safely land our Pilots in case everything fails (Make sure process doesn't die in case of any fatal error)
7. ### Test Launch
   * Let's create simulation environment for rocket (Setting up test suite)
   * Let's Test it (Writting test cases)
8. ### Launch Day
   * How to assemble the rocket on launch pad (Countinous Integration)
   * 5....,4.....,3.....,2....,1 Ignition (Deploy)
