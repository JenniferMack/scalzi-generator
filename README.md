# scalzi-generator

A script that keeps John Scalzi's "Standard Responses to Online Stupidity" as close as a click.

The original inspirational post can be found at: Scalzi's [Whatever blog](http://whatever.scalzi.com/2015/03/02/standard-responses-to-online-stupidity/).

## Usage

The script simply prints a random Response.

    $ ./scalzi_generator.rb 
    I didn't ask you.
    $ ./scalzi_generator.rb 
    I don't care what you think.

On a Mac, the output can be sent to the clipboard.

    $ ./scalzi_generator.rb | pbcopy

## Workflow

The `scalzi_generator.workflow.zip` unpacks into a workflow file that is used by the Automator app. From there it can saved as service for system wide Standard Response goodness.
