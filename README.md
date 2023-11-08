# jonjuguna2.github.io
/ __)  /__\  ( \/ )(_  _)( \( ) / __)  ( \/ )(  )(  )(  \/  )(  \/  )( \/ )( \/ )(_  _)(  )  (  )  ( ___)
\__ \ /(__)\  \  /  _)(_  )  ( ( (_-.   \  /  )(__)(  )    (  )    (  \  /  \  /  _)(_  )(__  )(__  )__) 
(___/(__)(__)  \/  (____)(_)\_) \___/   (__) (______)(_/\/\_)(_/\/\_) (__)   \/  (____)(____)(____)(____)
                                                   
                                  .-.
                                 /___\
                                 |___|
                                 |]_[|
                                 / I \
                              JL/  |  \JL
   .-.                    i   ()   |   ()   i                    .-.
   |_|     .^.           /_\  LJ=======LJ  /_\           .^.     |_|
._/___\._./___\_._._._._.L_J_/.-.     .-.\_L_J._._._._._/___\._./___\._._._
       ., |-,-| .,       L_J  |_| [I] |_|  L_J       ., |-,-| .,        .,
       JL |-O-| JL       L_J%%%%%%%%%%%%%%%L_J       JL |-O-| JL        JL
IIIIII_HH_'-'-'_HH_IIIIII|_|=======H=======|_|IIIIII_HH_'-'-'_HH_IIIIII_HH
-------[]-------[]-------[_]----\.=I=./----[_]-------[]-------[]--------[]-
 _/\_  ||\\_I_//||  _/\_ [_] []_/_L_J_\_[] [_] _/\_  ||\\_I_//||  _/\_  ||\
 |__|  ||=/_|_\=||  |__|_|_|   _L_L_J_J_   |_|_|__|  ||=/_|_\=||  |__|  ||-
 |__|  |||__|__|||  |__[___]__--__===__--__[___]__|  |||__|__|||  |__|  |||
IIIIIII[_]IIIII[_]IIIIIL___J__II__|_|__II__L___JIIIII[_]IIIII[_]IIIIIIII[_]
 \_I_/ [_]\_I_/[_] \_I_[_]\II/[]\_\I/_/[]\II/[_]\_I_/ [_]\_I_/[_] \_I_/ [_]
./   \.L_J/   \L_J./   L_JI  I[]/     \[]I  IL_J    \.L_J/   \L_J./   \.L_J
|     |L_J|   |L_J|    L_J|  |[]|     |[]|  |L_J     |L_J|   |L_J|     |L_J
|_____JL_JL___JL_JL____|-||  |[]|     |[]|  ||-|_____JL_JL___JL_JL_____JL_J
                       '-''--'--'-----'--'--''-'             
               (PRESS ENTER TO PLAY)               
");
            
        }
        public void Start()
        {
            Title = GameTitle;
            ForegroundColor = ConsoleColor.Magenta;
            WriteLine("Welcome Adventurer to the kingdom Yummyville!");
            WriteLine("What should you call you young adventurer?");
            player.Name = Console.ReadLine();


            WriteLine("Glad to meet you, Adventurer " + player.Name + "!");


            WriteLine("Welcome Adventurer to the kingdom Yummyville!");
            WriteLine("What should you call you young adventurer?");


            Console.Clear();

            WriteLine("Glad to meet you, Brave, " + player.Name + "!");
            WriteLine("I am Queen Sweetness, here to guide you on your journey...Press any key to START");

            Console.ReadKey();

            Console.Clear();

            WriteLine($"Queen Sweetness: {player.Name} We need your help, In Yummyville,a sweet kingdom filled with delicious eats.\r\nThe villain Captain Sour has taken my subjects the Treats\r\n The Treats that are being held captive by Captain Sour in his castle ship. The story\r\nasked to go on a journey to Captain\r\nSour’s castle ship, to rescue the treats and defeat Captain Sour. On your quest, you will be\r\nasked to make choices on where way to go and what artifacts to use when on your quest.");


            Console.ReadKey();

            Console.Clear();

            ForegroundColor = ConsoleColor.Blue;
            WriteLine("Queen Sweetness: Are you up for an adventure" + player.Name + "?");

            Console.ReadKey();

            WriteLine("Queen Sweetness: I will help you make decisions along the way, YOU GOT THIS!" + player.Name);

            Console.ReadKey();

            Console.Clear();

         

            WriteLine(player.Name + " and Queen Sweetness make your way to Cupcake Bridge.\r\n...But oh no the bridge is broken, what do we do?");
            Console.ReadKey();

            Console.Clear();

            WriteLine("Queen Sweetness: Check your backpack, what can we use to fix the bridge?");



            WriteLine("You have to make a choice\r\n1) Walking Pretzel sticks 2) Bouncy Beignets 3) Flying Fruit Tart  4) Rice Krispie Treat Bricks");
            string choice = ReadLine();
            switch (choice)

            {
                case "1":
                    player.PlayerChoice.Color = "Walking Pretzel sticks,YOU ARE ABLE TO WALK ACROSS THE BRIDGE WITH THE HELP OF YOUR GIANT PREZTEL STICKS!";

                    break;
                case "2":
                    player.PlayerChoice.Color = "Bouncy Beignets,YOU EAT THE BEIGNETS AND BOUNCE ACROSS TO OTHER SIDE OF THE BRIDGE...YAY!";
                    break;
                case "3":
                    player.PlayerChoice.Color = "Flying Fruit Tart,YOU EAT THE FRUIT TART AND FLYING ACROSS!";
                    break;
                case "4":
                    player.PlayerChoice.Color = "Rice Krispie Treat Bricks,YOU BUILD A NEW BRIDGE IN LIGHTNING SPEED AND WALK ACROSS TO THE OTHER SIDE!";
                    break;

            }


           
            Console.Clear();
            Console.WriteLine($"Congratulations, {player.Name}! You have chosen {player.PlayerChoice.Color}");
            Console.ReadKey();

            Console.Clear();

            ForegroundColor = ConsoleColor.Red;
            WriteLine(player.Name + " and Queen Sweetness make your way to Donut Cave.\r\n...But the entrance is blocked, what do we do?");
            Console.ReadKey();

            Console.Clear();

            WriteLine("Queen Sweetness: Check your backpack again, maybe their is something we can use to clear the path?");



            WriteLine("You have to make a choice\r\n1) Chocolate Lava Bombs 2) Super Strength Brownies 3) Freezing Ice Cream 4) Muffin Fists");
            string choices = ReadLine();
            switch (choices)

            {
                case "1":
                    player.PlayerChoice.Color = "Chocolate Lava Bombs,YOU ARE ABLE TO MELT THE BOULDER BLOCKING THE CAVE!";

                    break;
                case "2":
                    player.PlayerChoice.Color = "Super Strength Brownies, YOU LIFT THE BOULDER AND REMOVE THE IT FROM THE CAVE'S ENTRANCE...YAY!";
                    break;
                case "3":
                    player.PlayerChoice.Color = "Freezing Ice Cream,YOU EAT THE ICE CREAM AND HAVE FREEZING POWERS THAT FREEZES THE BOULDER AND BREAKS THE BOULDER TO GO THROUGH THE CAVE!";
                    break;
                case "4":
                    player.PlayerChoice.Color = "Muffin Fists,YOU BUILD MUFFIN FISTS AND OPEN UP THE ENTRANCE TO WALK THREW THE CAVE!";
                    break;

            }


            Console.Clear();
            Console.WriteLine($"Congratulations {player.Name}! You have chosen {player.PlayerChoice.Color}");
            Console.ReadKey();

            Console.Clear();

            ForegroundColor = ConsoleColor.DarkYellow;
            WriteLine("Queen Sweetness: Challenge completed! \r\n let's make our way to Cupcake Hill.\r\n...But how do we get over it, what do we do?");
            Console.ReadKey();

            Console.Clear();

            WriteLine("Queen Sweetness: Check your backpack again, what can we use to go over the hill?");



            WriteLine("You have to make a choice\r\n1)Flying Blondies 2) Creamsicles Skates 3)Cinnamon Sneezing Powder 4)Coconut Cream Pie Jetpacks");
            string chose = ReadLine();
            switch (chose)

            {
                case "1":
                    player.PlayerChoice.Color = "Flying Blondies,YOU ARE ABLE TO FLY OVER CUPCAKE HILL!";

                    break;
                case "2":
                    player.PlayerChoice.Color = "Creamsicles Skates, YOU ARE ABLE TO SKATE OVER THE HILL ...YAY!";
                    break;
                case "3":
                    player.PlayerChoice.Color = "Cinnamon Sneezing Podwer,YOU INHALE THE POWDER AND SNEEZE YOURSELF OVER THE HILL...ACHEW,BLESS ME!";
                    break;
                case "4":
                    player.PlayerChoice.Color = "Coconut Cream Pie Jetpacks,YOU FLY OVER THE HILL ON YOUR JETPACKS!";
                    break;

            }


            Console.Clear();
            Console.WriteLine($"Congratulations {player.Name}! You have chosen {player.PlayerChoice.Color}");
            Console.ReadKey();

            Console.Clear();

            ForegroundColor = ConsoleColor.Yellow;
            WriteLine("Queen Sweetness: Challenge complete\r\n let's make our way to Gooey Toffee Meadow.\r\n...But how do we get over it\r\nits so sticky, what do we do?");
            Console.ReadKey();

            Console.Clear();

            WriteLine("Queen Sweetness: Check your backpack again, what can we use to go over the meadow?");



            WriteLine("You have to make a choice\r\n1) Milk Spray Gun 2) Candied Jeep  3)Bubblegum Cloud 4)Jelly Beanstalk");
            string chos = ReadLine();
            switch (chos)

            {
                case "1":
                    player.PlayerChoice.Color = "Milk Spray Gun,YOU ARE ABLE TO SPRAY THE MEADOW AND GET ACROSS!";

                    break;
                case "2":
                    player.PlayerChoice.Color = "Candied Jeep, YOU ARE ABLE TO DRIVE OVER THE MEADOW...VROOM VROOM!";
                    break;
                case "3":
                    player.PlayerChoice.Color = "Bubblegum Cloud,YOU BLOW A BUBBLE GUM TO FORM A CLOUD TO FLOAT OVER THE MEADOW!";
                    break;
                case "4":
                    player.PlayerChoice.Color = "Jelly Beanstalk,YOU PLANT THEM AND IT CREATES A CLEAR PATH ACROSS THE MEADOW!";
                    break;

            }


            Console.Clear();
            Console.WriteLine($"Congratulations {player.Name}! You have chosen {player.PlayerChoice.Color}");
            Console.ReadKey();

            Console.Clear();

            Console.Clear();

            WriteLine("Queen Sweetness: You did it! Yipppee:) \r\n Queen Sweetness: Let's make our way to Caramel Dock.\r\n...But Captain Sour Ship is surronded by Sour Patches guarding the ship, what do we do?");
            Console.ReadKey();

            Console.Clear();

            WriteLine("Queen Sweetness: Check your backpack again, to get on the Sour ship?");



            WriteLine("You have to make a choice\r\n1)Candy Corn Rope  2) Hallucination Cookies  3)Invisible Granita 4)Banana Bread Monkeys");
            string choes = ReadLine();
            switch (choes)

            {
                case "1":
                    player.PlayerChoice.Color = "Candy Corn Rope,YOU ARE ABLE TO TIE THE SOUR PATCHES!";

                    break;
                case "2":
                    player.PlayerChoice.Color = "Hallucination Cookies, YOU ARE ABLE TO TRICK THE SOUR PATCHES TO EAT THEM AND IT THEM DELUSIONAL!";
                    break;
                case "3":
                    player.PlayerChoice.Color = "Invisible Granita, YOU ARE ABLE EAT THE GRANITA AND SNEAK PAST THE SOUR PATCHES!";
                    break;
                case "4":
                    player.PlayerChoice.Color = "Banana Bread Monkeys,THE MONKEYS ATTACK THE SOUR PATCHES!";
                    break;

                    Console.Clear();
                    Console.WriteLine($"Congratulations {player.Name}! You have chosen {player.PlayerChoice.Color}");
                    Console.ReadKey();

                    Console.Clear();

                    Console.Clear();

                    WriteLine("Queen Sweetness: Challenge complete\r\n Queen Sweetness: Let's make our way to Caramel Dock.\r\n...But Captain Sour Ship is surronded by Sour Patches guarding the ship, what do we do?");
                    Console.ReadKey();

                    Console.Clear();

                    WriteLine("Queen Sweetness: Check your backpack again, to get on the Sour ship?");

            }

                    Console.Clear();
                    Console.WriteLine($"Congratulations {player.Name}! You have chosen {player.PlayerChoice.Color}");
                    Console.ReadKey();

                    WriteLine("Queen Sweetness: Challenge complete\r\n Queen Sweetness: IT'S CAPTAIN SOUR AND HE HAS ME!\r\n... HELP ME!");
                    Console.ReadKey();

                    Console.Clear();

                    WriteLine("What do you do?");



                    WriteLine("You have to make a choice\r\n1)Attack  2) Rescue  3)Sneak 4)Magic");
                    string choic = ReadLine();
                    switch (choic)

                    {
                        case "1":
                            player.PlayerChoice.Color = "Attack,YOU ATTACK CAPTAIN SOUR AND QUEEN SWEETNESS TRANSFORM INTO A CHOCOLATE PUDDING!";

                            break;
                        case "2":
                            player.PlayerChoice.Color = "Rescue, YOU RESCUE THE TREATS, YOU AND THE TREATS ATTACK CAPTAIN SOUR AND CAPTURE HIM...HURRAY!";
                            break;
                        case "3":
                            player.PlayerChoice.Color = "Sneak, YOU SNEAK UP AND EAT CAPTAIN SOUR AND SAVE THE TREATS!"
                            break;
                        case "4":
                            player.PlayerChoice.Color = "Magic, YOU USE HEAT MAGIC AND MELT CAPTAIN SOUR AND SAVES THE TREATS AND QUEEN SWEETNESS!";
                            break;

                            


                    }

            Console.Clear();
            Console.WriteLine($"Congratulations {player.Name}! You have chosen {player.PlayerChoice.Color}");
            Console.ReadKey();

            Console.Clear();
            Console.WriteLine($"Queen Sweetness: You were so Brave ପ(๑•ᴗ•๑)ଓ ♡,YOU HAVE SAVED YUMMYVILLE {player.Name}!");
            Console.ReadKey();

            Console.Clear();
            Console.WriteLine($"Treats: Your awesome, {player.Name} \r\n Comeback and Play again ꒰ᐢ..ᐢ꒱₊˚⊹ !");
            Console.ReadKey();

        }
        public void End()
        {

            string End = "";
            Console.WriteLine(@"


/ __)  /__\  ( \/ )(_  _)( \( ) / __)  ( \/ )(  )(  )(  \/  )(  \/  )( \/ )(_  _)(  )  (  )  ( ___)
\__ \ /(__)\  \  /  _)(_  )  ( ( (_-.   \  /  )(__)(  )    (  \  /  \  /  _)(_  )(__  )__) 
(___/(__)(__)  \/  (____)(_)\_) \___/   (__) (______)(_/\/\_)(_/\/\_) (__)   \/  (____)(____)(____)(____)
                                                   
                           ⠀⠀⠀⠀⠀⠀⠀⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠠⢿⣿⠇⠀⠀⠀⣴⣦⠀⠀⠀⠀⠀⠀⠀⠀⣀⣤⠀⠸⠿⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠁⢠⡄⠀⠀⠀⠀⠀⠀⠀⠀⠀⣀⣤⣼⣯⣅⠀⠀⠀⠀⠀
⠀⠀⠀⠀⢀⣤⡀⠀⠀⠀⠹⣆⠀⠀⠀⠀⠀⠀⣠⠞⠋⣿⡇⢀⣽⠇⠀⠀⠀⠀
⠀⠀⠀⠀⠘⠛⠃⠀⢤⣤⣤⣿⣦⠀⠀⠀⠀⣰⣏⣀⡀⠘⠛⠛⠉⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠈⢿⡄⠀⠀⠀⢀⣴⢾⣿⠉⠉⣿⠀⠀⠀⠐⣾⣷⠄⠀⠀
⠀⠀⠀⠀⠀⠀⢀⣀⣀⠀⠀⠀⠀⠀⣾⠃⠀⠻⣶⠾⠋⠀⠀⠀⠈⠈⠁⠀⠀⠀
⠀⠀⠀⠀⠀⠀⢻⣿⣿⣿⣶⣄⠀⠸⠏⠀⠀⠀⠀⠀⢀⡀⠀⠀⠀⠀⠀⢀⡀⠀
⠀⠀⠀⠀⠀⣦⠈⢿⣿⣿⣿⣿⣷⣄⠀⠀⠀⣤⡀⢠⡿⠻⣦⣀⣠⣴⠾⠛⠁⠀
⠀⠀⠀⠀⠸⣿⣷⣄⠻⣿⣿⣿⣿⣿⣷⡄⠀⠈⠻⠟⠁⠀⠈⠉⠁⠀⠀⠀⠀⠀
⠀⠀⠀⠀⣄⠙⠻⣿⣷⣌⠻⣿⣿⣿⣿⣿⡄⠀⠀⠀⢠⣶⡄⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠸⣿⣿⣦⣈⠙⠿⣷⣄⠙⠻⠿⣿⠇⠀⠀⠀⠀⠉⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⢠⣦⣈⠙⠿⣿⣷⣦⡄⠉⠛⠂⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⣼⠿⠿⠛⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀   
               (COMEBACK AND PLAY AGAIN ૮꒰ྀི⸝⸝> . <⸝⸝꒱ྀིა)               
