# How To Add A Custom Boot-Up Message?
In this tutorial you will learn how to make a custom boot-up message to start your terminal.

## Setting Up The Message
1. Go into Windows terminal and run the following command:
```
New-Item -Path $PROFILE -Type File -Force
```
2. Then, run the command:
```
notepad $PROFILE
```
3. This will open up a notepad where you can write anything. Note: Anything you write must be in " " or, for multiple lines, in @" "@.

## Setting Up The Vault Boy
1. Copy this ASCII art with the multi-line string quotes: (It might be better to manually copy instead of clicking the copy button.)
```
@"                       
                                                                                            @@@@                                                                 
                                                                                          @@. ..@@@                                                              
                                                                                   @@=.@@@..........=@@                                                          
                                                                           @@@   @@.. .................@                                                         
                                                                          @...@@@.. ........  ..........@@                                                       
                                                                          @  ......@@@@@.@@@@@@+.....   ..@                                                      
                                                                          @@.....@@            @@...@@@@...@#                                                    
                                                                          @ @..@@                      .@...@                                                    
                                                                         #@..@  @@           @          @@...@                                                   
                                                                          @.@                @@@      @@ ....@                                                   
                                                                           @                          .@.....@                                                   
                                                                          @   :@@    @@     @         @: @. @                                                    
                                               @@@@@                      @   .@=   @@     @@         @ @ @.@                                                    
                                            @@      @@                   @         @.                @  % @@                                                     
                                           @.       @                    @       @@                    @ @@                                                      
                                           @       @-                    @        @@%                 @   @                                                      
                                          @#      *@                     @                .@              @                                                      
                                           @      @                      @+ @@@@@  .   @@@.@@@            @                                                      
                                            @     @@                      @  @@           @@ @           @                                                       
                                            @      %@                     @@     @@@@@@@:            @@@.                                                        
                                     @@@@@@@@@@@     @@                    @@     @%@              @@                                                            
                                   @@            @@    @@                   @@                    @                                                              
                                   @-              @    @@                    @-               @@@@@@=                                                           
                                    @@@@@@@@@@     @     .@@@                @@@@@               @   .@@@@                                                       
                                    @         =@@@@@     -.--=@@@@@@@%##@@@@#@   ..@@@         @@ .  .@---+@@@                                                   
                                   @              @     @..#+=--------=------+@..   @@@@@@@@@@=   .  @@-==----@@@                                                
                                    @              @   @@ *+=================-+@@                   @@--======---@@                                              
                                     @@@%#@@@@@@   @  @@  @-+==================-+@@@     ......  -@@=--=========---@@.                                           
                                    @            @@    @ .@-===================+=---@@@@@  .. . @@---==============--*@                                          
                                    @    @        .   @. @%-===============+========----@ ....  @--======--==========--@@                                        
                                     @@    @@@@@@@@ @@   @-==============:---==========-@.  . . .@======-@-===========---@#                                      
                                       @@@:      :@@.  .@*-===========----@%-============@ ... . @+=====-@--============--@@                                     
                                             +.  @@ . @@--=++++=-----*@@@@---============@...... .@-====-+@-=============--@@                                    
                                                    @ @@@@@@@@@@@@@@@. @#--==============@. .... .@-=====-@-=-----========--@@                                   
                                                                        @-===============@:...... %%-+===-@---*@+-=========-%@                                   
                                                                        @-===============+@ ...... @-+===--+-%@--==========-@                                    
                                                                        @-===============-@  ......@======-*-@--==========-@%                                    
                                                                        @-=+=============-@....... @-=====-@@:-==========-#@


"@
```
2. Paste this into the notepad.
3. Ctrl + S to save the notepad.
4. Lastly, close out of it and restart Windows terminal. If everything was done correctly you should see your message and the Vault Boy.

## Fullscreen For Better Experience
1. Open up the terminal settings.
2. On the sidebar, click "Startup".
3. Scroll down to "Lauch Parameters".
4. Click on "Launch Parameters".
5. Click on the drop-down for "Launch Mode", and click "Maximized".
