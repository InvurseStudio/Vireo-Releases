# Vireo privacy policy

_Last updated November 19, 2026, for Vireo 0.9.1._

Vireo (formerly InvurseChat) is made by Invurse Studio. It runs AI models on your own Mac, and
it's built so that your conversations stay with you.

## What we collect

Nothing. Vireo has no accounts, analytics, crash reporting, advertising
or tracking. Invurse Studio doesn't receive your chats, files, prompts or
usage information, and has no servers that could.

## Where your data lives

- **Chats and settings** are saved as files on your Mac, in
  `~/Library/Application Support/Vireo`.
- **The model** runs on your Mac, on Vireo's own engine (Syrinx). Your messages
  are not sent to any AI service. The engine only accepts connections from your
  own Mac.
- **Files you attach** are read on your Mac, and a copy is kept with the chat.
- **Scheduled tasks** you set up run on your Mac, and their results are saved as
  chats like any other. Changes a task wants to make wait for your approval,
  unless you chose "Don't ask again" for that kind of change. A task can also
  start when new files arrive in a folder you choose, or when its private link is
  opened on your Mac.
- **Calendar and Reminders** are read on your Mac once you allow access in
  macOS. The assistant asks you before it adds, moves, changes or completes
  anything, unless you chose "Don't ask again" for that kind of change, and
  always asks before deleting. Vireo doesn't copy them anywhere. Event details
  the assistant reads become part of that chat.
- **Voice.** When you ask Quick Ask by voice, or turn on the wake word, your
  speech is turned into text on your Mac with Apple's on-device speech
  recognition. Audio isn't saved or sent anywhere. The wake word is off until you
  turn it on.
- **Memory** holds facts you ask the assistant to remember. It asks before
  saving one. Facts are stored on your Mac and added to your chats'
  instructions. You can see, edit or delete them in Settings › Memory, or turn
  memory off.
- **Earlier chats.** So the assistant can find something you discussed before,
  it searches your chats on your Mac.
- **Skills** are files on your Mac. The assistant saves or changes one only when
  you ask and approve it.
- **Contacts** are read only to find the number or address of someone you ask
  the assistant to message, once you allow access in macOS.
- **Messages** are sent only when you ask the assistant to message someone. It
  shows you the message and asks first, unless you chose "Don't ask again" for
  messages. They go from your own Messages account, like any message you send.
- **Your screen.** When you ask about what's on screen, the assistant reads it
  with Apple's on-device text recognition. It asks first, unless you chose
  "Don't ask again", and needs macOS's Screen Recording permission. The image
  isn't saved or sent anywhere; the text it reads becomes part of that chat.
- **Shell commands and Shortcuts** run only when you ask, and the assistant asks
  before each one. A command or shortcut can do anything it was built to do,
  including going online, and Vireo can't undo it.
- **Undo copies.** When the assistant changes or replaces a file, it keeps a
  private copy of what was there on your Mac, so **Undo this run** can put it
  back. Copies are deleted after 14 days. Files it deletes go to your Trash.

You can delete chats in the app. Uninstalling the app and removing
`~/Library/Application Support/Vireo` removes everything it stored. If you used
Vireo 0.9 or earlier, its files are in `~/Library/Application Support/InvurseChat`
until you remove them (Settings › Advanced › Files from Vireo 0.9 does this).

## When the app goes online

Vireo connects to the internet only for these things:

| When | Service | What it receives |
| --- | --- | --- |
| The app checks for updates (about once a day if you allow it, or when you choose Check for Updates) | GitHub, where releases are published | A normal download request, which names the app and its version |
| You download or search for a model | Hugging Face | The name of the model or search |
| A request needs the web (for example, you ask about current events) | DuckDuckGo, with Bing as a fallback | The search words |
| The assistant opens a web page | That website | A normal page request |

These services have their own privacy policies. The app never sends your chat
history to them, only what the request needs.

## Other apps

The OpenAI-compatible API is off until you turn it on in Settings › Developer.
Then apps on your Mac can use your model through it, with an API key if you ask
for one. Other devices can't reach it.

## Children

Vireo isn't directed at children under 13, and it doesn't knowingly
collect anyone's information.

## Changes

If this policy changes, the new version will be posted here with a new date.

## Contact

Questions: [hello@invursestudio.com](mailto:hello@invursestudio.com)
