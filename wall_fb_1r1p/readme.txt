<!-- =================================================================================== -->
<!-- |    Author: Yeshasvi Tirupachuri                                                 | -->
<!-- |    Date: 16 MARCH  2017                                                           | -->
<!-- |    Email: Yeshasvi.Tirupachuri@iit.it                                           | -->
<!-- |    Institute: RBCS Department, Italian Institute of Technology, Genova          | -->
<!-- |    Description: Floating base 1R1P two link systems  attached to a wall         | -->
<!-- =================================================================================== -->

Floating base 1R1P 2 Link system with one link attached to a wall

The SDF file produced using URDF is displayed as white visually in Gazebo. Modify the visual elements with material elements as shown belows

<visual name='base_link_visual_1'>

        <pose frame=''>0 0.025 -0.0125 0 -0 0</pose>
        <geometry>
          <box>
            <size>0.05 0.1 0.025</size>
          </box>
        </geometry>

        <material>
          <script>
            <name>Gazebo/DarkGray</name>
            <uri>file://media/materials/scripts/gazebo.material</uri>
          </script>
        </material>

</visual>

COLORS:

Gazebo/Grey
Gazebo/GreyTransparent
Gazebo/DarkGrey
Gazebo/White
Gazebo/FlatBlack
Gazebo/Black
Gazebo/Red
Gazebo/RedTransparentOverlay
Gazebo/RedTransparent
Gazebo/RedBright
Gazebo/Green
Gazebo/GreenTransparentOverlay
Gazebo/GreenTransparent
Gazebo/Blue
Gazebo/BlueTransparentOverlay
Gazebo/BlueTransparent
Gazebo/SkyBlue
Gazebo/Yellow
Gazebo/YellowTransparent
Gazebo/ZincYellow
Gazebo/DarkYellow
Gazebo/Purple
Gazebo/Torquoise
Gazebo/Orange
Gazebo/OrangeTransparentOverlay
Gazebo/DarkOrangeTransparentOverlay
Gazebo/Indigo
Gazebo/DarkMagentaTransparent


Gazebo/WhiteGlow
Gazebo/RedGlow
Gazebo/GreenGlow
Gazebo/BlueGlow
Gazebo/YelloGlow
Gazebo/PurpleGlow
Gazebo/TorquoiseGlow
Gazebo/TorquoiseGlowOutline
