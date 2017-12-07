# Table_Pong_AI

## Welcome
Welcome to the documention of the table pong AI's.

You can write your own AI and submit them to add them to the actual table :-)

## Naming
The name of the AI must be formated like so : AI_EXAMPLE.PONG
and a folder must be next to the .pong file with all the need resources.
All the names of files and the folder must be **IN CAPITALS LETTERS !**

The .WAV files must be 16 bit PCM, 44100 Hz WAV. ~stereo~ or mono and named like so:
AI_NAME_THENAMEOFTHESAMPLE.WAV
Again with only capials letters and no spaces.
You can afterwards put the name of you file in the .PONG file

## The .pong File
 **AI_name** _string_ max 8 chararacters. This is the name displayed
 **AI_description** _string_. A description of your AI.
 **AI_version** _int_. The version of your AI. You must increment it if you want the table pong select the right files.
 **AI_authors_logins** _array_. Contain one or multiple authors logins.
 **AI_react** _int_ in ms. The latency between the AI decision and reaction.
 **AI_precision** _int_ in %. The accuracy of the AI.
 **AI_error** _int_ in %. The error percentage of the AI decisions.
 **AI_speed** _int_ in %. The speed of the AI travelling. This is really usefull for beginers AI.
 **AI_wait_for_ready** _bool_. If this is true the AI will wait wou make an input before launching the ball. Again this is also usefull for beginers.
 **AI_on_menu** _sting_. The sound played when you scroll the menu.
 **AI_on_menu_selected** _string_. The sound played when you select an AI.
 **AI_wavs** _object_. Contains all the wavs of the AI configuration.
    **AI_on_start** _array_. .WAV played randomly when the game starts.
    **AI_on_round_loose** _array_. .WAV played randomly when the AI loose a round.
    **AI_on_round_win** _array_. .WAV played randomly when the AI win a round.
    **AI_taunts** _array_. .WAV played randomly when the AI is waiting.
    **AI_on_loose** _array_. .WAV played randomly when the AI loose the game.  
    **AI_on_win** _array_. .WAV played randomly when the AI win the game.

## Licence
The table pong AI's must be under the licence MIT.
