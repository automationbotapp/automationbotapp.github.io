---
# layout: page
title: ChonkaBot
permalink: /chonkabot/
---

<h2>ChonkaBot</h2>
<table style="background-color: rgba(66, 66, 66, 0.87); color: rgba(255, 255, 255, 0.87); text-align: left; width: 100%;">
  <tr>
    <th>Command</th>
    <th>Response</th>
    <th>Role</th>
    <th>Editable</th>
  </tr>
  <tr>
    <td title="Answer a question." style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!askchonka</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Ask and find out!</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">No</td>
  </tr>

  <tr>
    <td title="Quick Pokébattle with another viewer!" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!battle</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">${battleResults}</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">No</td>
  </tr>

  <tr>
    <td title="Bot training for updating commands." style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!chonkabot</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">@${user} Consider it done!</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Moderator</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">No</td>
  </tr>

  <tr>
    <td title="Create a clip for Curlie!" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!clip</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">@${user} One clip, coming right up... curlieqCynda</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">No</td>
  </tr>

  <tr>
    <td title="Tell the chatter their randomly generated cute percentage." style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!cute</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">curlieqLove @${user}, you are ${cuteness}% cute today! curlieqComfy</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">No</td>
  </tr>

  <tr>
    <td title="Say how many days since Pokémon Unite last released a defender." style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!defender</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">It's been over ${days} days since Unite added a new defender... just sayin' curlieqMurder</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">No</td>
  </tr>

  <tr>
    <td title="" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!followage</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">${user} has been following CurlieQ for ${followTime} curlieqJam</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">No</td>
  </tr>

  <tr>
    <td title="Create a stream marker for Curlie, don't forget to include a description!" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!marker</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">A stream marker was created by @${user} at ${streamTime}s.</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">No</td>
  </tr>

  <tr>
    <td title="Tell the chatter basic information about a specific Pokémon from the Pokédex." style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!pdb</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">@${user} Here's what I know about [#${pokemonId}] ${pokemonName} ... ${pokemonData}</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">No</td>
  </tr>

  <tr>
    <td title="Tell the chatter their randomly generated Pokémon for the day (global Pokédex)." style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!pickemon</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">curlieqWave @${user}, your Pokémon for today is: ${pokemonName}! Congrats! curlieqEspeon</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">No</td>
  </tr>

  <tr>
    <td title="Ask a Pokémon Unite quiz question in the chat" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!popquiz</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Pop Quiz: ${quizQuestion} curlieqEspeon</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">No</td>
  </tr>

  <tr>
    <td title="Set the giveaway command for auto responses." style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!setgiveaway</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">@${user} Giveaway command set to !${gaCommand}</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Moderator</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">No</td>
  </tr>

  <tr>
    <td title="A slap from one chatter to another... mostly." style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!slap</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">${randomResponseWhereSlapperSlapsSlappee}</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">No</td>
  </tr>

  <tr>
    <td title="Takeover the StreamElements commands as best I can." style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!takeover</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">🟢 or 🔴 depending whether this has been switched off or on.</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Moderator</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">No</td>
  </tr>

  <tr>
    <td title="Tell the chatter type information about a specific Pokémon Type from the Pokédex." style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!tdb</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">@${user} ${typeName} types are... weak to: ${weakTo}; and strong against: ${strongAgainst}</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">No</td>
  </tr>

  <tr>
    <td title="Tell the chatter their randomly generated toxic percentage." style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!toxic</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">curlieqZorua @${user}, you are ${toxicity}% toxic today! curlieqGengar</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">No</td>
  </tr>

  <tr>
    <td title="Translate a phrase to English if it's not NSFW" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!translate</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;"></td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Moderator</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">No</td>
  </tr>

  <tr>
    <td title="Choose a random Pokémon from the Pokémon Unite roster for the chatter." style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!unitespin</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">@${user} Your random Unite Pokémon is ... *drumroll* ... ${pokemon}! GLHF! curlieqMonka</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">No</td>
  </tr>

  <tr>
    <td title="Let everyone know who's playing in the current slot" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!whosplaying</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">@${user} For the current slot we have... ${players} curlieqJam</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">No</td>
  </tr>


</table>
<h2>StreamElements</h2>
<table style="background-color: rgba(66, 66, 66, 0.87); color: rgba(255, 255, 255, 0.87); text-align: left; width: 100%;">
  <tr>
    <th>Command</th>
    <th>Response</th>
    <th>Role</th>
    <th>Editable</th>
  </tr>
  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!1</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">psykey number 1 absol NA</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!4years</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">peepoBirthdayConfetti happy birthday to QREW peepoBirthdayConfetti happy birthday to QREW peepoBirthdayConfetti happy birthday dear CURLIE QREW peepoBirthdayConfetti happy birthday to QREWWW peepoBirthdayConfetti</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!7tv</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">goomySpin BLANKIES SquirtleJam zoruaHehe EspurrShooketh If you can't see these emotes, it's because you don't have 7TV! Don't wait a million years to download it like Curlie did. Get the extension TODAY! https://7tv.app/</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!absol</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">psykey number 1 absol NA</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!ah</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">frick!</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!allrounder</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Psykey is the #1 all rounder NA</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!anni</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">CURLIE CONGRATS ON PARTNER YOU'RE LITERALLY NUTTY YOU DESERVE ALL OF YOUR SUCCESS YOUR COMMUNITY LOVES YOU AND YOU SPREAD YOUR LIGHT WHEREVER YOU GO YOU DO SO MUCH FOR THE PEOPLE AROUND YOU AND IF THIS COMMAND WAS USED IT'S BECAUSE THE PERSON THAT USED IT WANTS YOU TO KNOW THAT YOU'RE AN INSPIRATION AND YOU MEAN A LOT TO THEM AND YOUR SPACE IS CHERISHED AND APPRECIATED!!!!!!!!!!! CONGRATS WE LOVE YOU CURLIEQ</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!announcement</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Curlie is aware of the issues floating around in the unite community. We are not going to discuss it here though to ensure that this space stays as a form of relief and escape. If you wish to see curlies stance on the matter, she has publicly made a statement in the announcement channel of the Qrew Discord Server.</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!apresser</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">PRESS A TO CONTINUE</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!artist</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">curlie actually owns the school davinci went to where he painted the mona lisa <3</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!backseat</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Just a reminder to please allow Curlie the chance to experience the game in her own way. Your message may be deleted if a mod feels you are giving too much unsolicited help. If Curlie has a question, she will ask.</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!bark</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">GRRRRRRR WOOF WOOF BARK BARK ARF ARF BARK WOOF WOOF GRRRRR SNARL SNARL HSSSSSSS GRRRRRRR WOOF BARK ARF BARK SNARL WOOF WOOF BARK ARF GRRRRRRR WOOF WOOF BARK BARK ARF ARF BARK WOOF WOOF GRRRRR SNARL SNARL HSSSSSSS GRRRRRRR WOOF BARK ARF BARK SNARL</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!bcl</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">BetterCrewLink download here: https://github.com/OhMyGuus/BetterCrewLink/releases/latest</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!birthday</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Happiest of birthdays to the one and only $(user)! Much love from the Qrew <3</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!blastoise</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Focus/Buddy/Energy amp - Hydro/Water Spout + Spin</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!bluebuff</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Blue Bluff! curlieqChonka</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!booty</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">DANCE shake da booty to da beat DANCE shake da booty DANCE shake da booty DANCE shake da booty DANCE shake da booty to da beat</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!bottom</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">https://youtu.be/QHjWNjrobrs?t=3</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!britt</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">@algaeturtles protector.. AKA @himynameisshain 's worst enemy</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!bttv</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">/me Get access to BTTV emotes by going to https://betterttv.com/ and downloading the extension for your browser!</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!bug</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Fire, Flying, Rock</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!bugabuse</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">But CURLie iT'S in The gAME. ANd if It's iN The gaMe TheN iTs a FEaUTre tHE dEV'S MUSt ObvioUsly WaNt US tO Use. I'M oNlY doinG WHatS ALLoWed IN GAme.</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!catears</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">They do look like cats ears! But it's just a cushion... Sadge Actual cat ears wen?!</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!charity</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">We're on the Quest to Conquer Cancer with The Princess Margaret Cancer Foundation - One of the top 5 cancer research foundations in the world! Use !donate to access the link to make a donation today</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!chonka</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">curlieqChonka I am chonka curlieqChonka</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!comfey</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">COM-FAY</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!cs</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Community Standards Rules: lobby code will be posted in chat, first-come-first-served; but give chance to others if you've played already today. Three games per group, please stay for all 3! Wheel participation is highly encouraged for maximum fun! Also, don't be a goober and glhf!  curlieqChonka</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!cure</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">spelling "cute" wrong is super cute, 100% no notes</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!curlie</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">my canadian queen curlie. i can’t talk bad about you. you go have fun and i hope you have a great rest of your day</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!curlieqttv</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">https://open.spotify.com/playlist/0CvhzFy37TcEe6T6BTojoy?si=494a7b3cb0b44745</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!curliesqueue</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">https://www.reddit.com/r/CurliesQueue/</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!dadjoke</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">This better be a good one curlieqChonka</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!dance</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">curlieqUwu You can dance if you want to curlieqUwu You can leave your friends behind curlieqUwu </td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!dark</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Bug, Fairy, Fighting</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!decaf</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">PSA: Curlie has not had any caffeine today, therefore cannot be held liable for her level of sass. DIDSOMEONESAYFOOD</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!diana</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Hey guys i'm a animation artist i help streamers grow their channel and make them logo, banner, emotes, overlays, vtubers and much more so if any of you is interested so they can drop their discord i'll show them my work and share my clients review with them</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!discord</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Come hang out with the Qrew outside of stream! Get access to bonus streams and become a part of our community! https://discord.gg/kpxsfMT</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!donate</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Curlie is going to GameConCanada! Any donos to help with costs greatly appreciated curlieqHiyah https://streamelements.com/curlieq/tip curlieqHiyah</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!donwloads</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">We are aware that "downloads" is spelled incorrectly. It is not Curlie's doing and she cannot fix it, so please ignore! <3</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!dragon</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Dragon, Fairy, Ice</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!duck</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">tha DUCK may THWIM on tha lake, but mah daddy OWNS tha lake curlieqTsareena</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!dumpy</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">GengarDumper CharizardPls slowpokeSus LugiaPls laxB</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!egghead</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">when's the last time YOU'VE been to papa john's ReallyMad</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!electric</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Ground</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!eleki</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">WRONG</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!eme</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">nice one @thanatosdriver</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!emotes</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">curlieqEspeon curlieqJam curlieqWave curlieqBop curlieqBlastoise curlieqBulba curlieqDed curlieqGrowlithe curlieqLax curlieqSwinub curlieqGengar curlieqEevee curlieqDerp curlieqGoodra curlieqCynda curlieqDairyQ curlieqKricketune curlieqMurder curlieqOshawott curlieqRaichu curlieqRowlet curlieqSlowbro curlieqSprigatito curlieqTsareena curlieqWobbuffet curlieqZorua</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!english</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">This is an English Twitch Channel! Please only use English in the chat. Any other messages will be deleted. If you can't speak or understand English this may not be the stream for you. Any translations that break the rules will result in an immediate ban.</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!espeon</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Psykey is the best Espeon in the wild Wild West</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!eyes</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">👁️ 👁️</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!fairy</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Poison, Steel</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!familyfriendly</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">We're all for LOLz, but also trying to keep this space family-friendly! Please try to keep the chat respectful and appropriate for all ages. Thanks! curlieqLove </td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!fan</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">If CurlieQ has a million fans, then I am one of them. If CurlieQ has ten fans, then I am one of them. If CurlieQ has only one fan then that is me. If CurlieQ has no fans, then that means I am no longer on earth. If the world is against CurlieQ, then I am against the world.</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!farm</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">To Whom It May Concern: Any wild Pokemon, or "farm," have been hereby claimed by the undersigned, CurlieQGamer, and she is legally allowed to take any piece of said farm under Section 4.20 of the CurlieQode. If you have any objections, please forward them to @ChonkaBot, who will not take care of them because Chonka cannot read. Sincerely, The Qrew</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!favorite</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">CurlieQ doesn't pick favorites bc she doesn't want all the other options to get their feelings hurt  Stare</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!favorites</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Curlie is allowed to pick one of her favorites if it’s in the starters. Current favorites are Blastoise, Lapras and Mew</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!feelings</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">I'm the only bot with feelings around here! curlieqLove</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!ffz</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">/me To view FFZ emotes, please go to https://www.frankerfacez.com/ and connect your twitch account!</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!fighting</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Fairy, Flying, Psychic</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!fire</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Ground, Rock, Water</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!flying</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Electric, Ice, Rock</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!focus</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">https://clips.twitch.tv/UnsightlyCharmingFinchArgieB8-QR8Ee2Gk2Vkxtdak</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!followeronly</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">For several months we have been dealing with follow botting and chat spam, so for the comfort of our streamer and the community chat is in follow-only mode! Apologies for any inconvience this may cause! curlieqBesties </td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!frick</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">frick curlieqChonka</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!gamedev</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">yeah curlie actually created the whole p0kem0n franchise in 4 years while becoming a streamer <3</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!genuinethanks</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">YEA OK DUDE</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!ghost</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Dark, Ghost</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!giveaway</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Curlie is giving away 1 Falinks license code! To qualify, you must have whispers turned on & follow the stream before the draw to receive a code if you win - use !falinks to enter</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!goblin</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">curlie is a loot goblin. she's gobblin up that loot. that little goblin under the bridge? that's curlie, waiting for loot. sableye isn't the goblin you think it is. curlie is the real goblin. the loot goblin. goblin of loot. if you spell curlie in another language. it's curlie q</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!gocurlie</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">CURLIE, CURLIE, SHE'S 👩 OUR 👵💰 GIRL! 👧🏽 IF SHE 💁‍♀️💁‍♀️💁‍♀️ CAN'T ❌ DO 🏆 IT, SHE 🧏 WAS JUST 🚟 KIDDING 💯 AND THAT 👏 WAS A JOKE 🥵😝 RUN 🏃🏼‍♂️ AND WE 👨‍👩‍👦 WERE 🎈 ALL 👵 JOKING AND IT WAS FUNNY 😃🍺😛😃 AND EVERYONE 🥰 LAUGHED 😂 AND NOW 📜 SHE'S 👩 GONNA 😰 DO 💃🏻 IT FOR 🎅 REAL ✅ THIS TIME 😰</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!goodluck</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">good luck with solo q... highly suggest finding a friend... terrible randoms... 2k talonflame getting mad on mic and yelling at jungler who did everything RIGHT!</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!grass</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Bug, Fire, Flying, Ice, Poison</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!greenbone</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">The clan is my blood, and the Pillar is its master!</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!ground</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Grass, Ice, Water</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!hatterene</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Hatterene should be in Pokémon Unite. This message was approved by CurlieQ.</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!hbd</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;"> peepoBirthdayConfetti  peepoBirthdayConfetti  peepoBirthdayConfetti  peepoBirthdayConfetti HAPPY BIRTHDAY TO OUR CANADIAN QUEEN  peepoBirthdayConfetti  peepoBirthdayConfetti  peepoBirthdayConfetti  peepoBirthdayConfetti</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!helditems</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">WHAT ARE THOOOOOOOOOOOSE!</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!helpme</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">just don't die?????</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!hidingcodes</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">she is NOT doing that</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!highfive</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">/me $(sender) high fives $(user) HeyGuys</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!highfiveall</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">/me $(sender) high fives everyone in the stream! HeyGuys</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!himinimishin</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">GESUNDHEIT!</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!horse</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">This game is similar to the basketball game HORSE if you've played it before! Curlie will spin a wheel to see what pokemon she has to play and whoever does the role of that pokemon best (attacking, tanking, healing or scoring) will win the round! The loser will get the letter "H" (and then "O", then "R", etc.) and the first one to get all five letters (aka spell HORSE) loses!</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!hug</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">/me $(sender) hugs $(user) PrideGive PrideTake</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!hugall</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">/me $(sender) hugs everyone in the stream PrideGive PrideTake</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!hustle</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">ITS ELECTRIC doo doo doo doodoo doodoo doo doo, doo doo doo doodoo doodoo doo doo  pikaD</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!hydrate</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">/me Get yourself some high quality H2O</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!hype</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">curlieqPog dittoPride DANCE DANCE DANCE dittoPride curlieqPog Let's get some HYPE! curlieqPog dittoPride DANCE DANCE DANCE dittoPride curlieqPog</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!ice</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Fighting, Fire, Rock, Steel</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!jackbox</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">We're playing Jackbox Party! Games are sub-only to help avoid random trolls. To join go to https://jackbox.tv and enter the code from the Discord #suberoni-chat thread! curlieqLax</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!joe</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">SHUT UP DANKO</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!joycons</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Curlie plays with split joycons as it's easier for her to do Stream Things™️  and she prefers them to the pro controllers!</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!krow</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">I CAN'T MUTE IT!</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!lacarpas</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Larpas KACHOW Larpas KACHOW Larpas KACHOW Larpas KACHOW Larpas KACHOW Larpas KACHOW Larpas KACHOW Larpas KACHOW Larpas KACHOW Larpas KACHOW Larpas KACHOW Larpas KACHOW</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!larpas</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Larpas larpasFRUIT LarpasJAMMER larpasLaser larpasSpin larpasSus larpasBean</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!lasarpas</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;"> Larpas  Lasagna  Larpas  Lasagna  Larpas  Lasagna  Larpas  Lasagna  Larpas  Lasagna  Larpas  Lasagna  Larpas  Lasagna  Larpas  Lasagna</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!letter</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;"> https://community.pokemon.com/en-us/discussion/8396/message-from-the-producer-dec-1-2023</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!lootgoblin</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">are you sure you need that Curlie?!? curlieqMonka</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!lotus8</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Curlie is a member of Lotus 8 Esports, a competitive and creative esports team, pioneers of mental health & fitness https://linktr.ee/Lotus8esports #WeAreLotus8 curlieqBlastoise</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!lozplaylist</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">https://open.spotify.com/playlist/2OJqa7ZVIggAPuegGZDt58?si=d3b79abe3efa4caa</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!lurk</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">/me ${user}, your presence is felt! Thank you for your support and enjoy your lurk! curlieqLurk</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!maam</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">ma'am pls stream on YT instead of twitch pls ma'am. big fan btw. ma'am pls replyyy</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!machamp</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">awww:(((( ooo big man missed his unite move:(((( sad:((((</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!main</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">curlie's current main is scizor and it might just be the hero we needed curlieqSprigatito</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!mamo</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">i pick things up curlieqUwu i throw them down curlieqUwu  i pick things up curlieqUwu i throw them down curlieqUwu</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!mentalhealth</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">If you're struggling with your mental health, it's important to seek help from professionals. Check this list of global helplines: http://bit.ly/GlobalHotlines ❤</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!merch</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">You love it here, and you wanna represent? Let me hook you up! Grab your CQ and Chonka merch here: https://curlie-shop.fourthwall.com/ curlieqHappi</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!merchclaim</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">https://curlie-shop.fourthwall.com/redeem</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!miami</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">no money 💰 no family🤧 16 in the middle of miami🌴 no money 💰 no family🤧 16 in the middle of miami🌴 no money 💰 no family🤧 16 in the middle of miami🌴 no money 💰 no family🤧 16 in the middle of miami🌴 no money 💰 no family🤧 16 in the middle of miami🌴 no money 💰 no family🤧 16 in the middle of miami🌴 no money 💰 no family🤧 16 in the middle of miami🌴 no money 💰 no family🤧 16 in the middle of miami🌴 no money 💰 no family🤧 16 in the middle of miami🌴 no money 💰 no family🤧</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!modfree</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">catJAM We catJAM Cat catJAM We catJAM Jam catJAM No catJAM Mod catJAM No catJAM Ban catJAM</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!murdergoss</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">https://youtu.be/pRyBKntaDZs</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!mute</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">curlieqMuted @CurlieQ curlieqMuted YOU'RE curlieqMuted MUTED curlieqMuted </td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!mutepings</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">+ go to name and then press A</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!na</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">psykey number 1 absol NA</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!neverforget</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">@CurlieQgamer you made a huge impact in your community in a way that you are always communicating with us and try to help with out problems as well as allow us into yours. you are truly an amazing streamer that will forever be in our hearts. I wish we knew each other in real life as we would get along SUPER WELL! <3 the way you help and talk to everyone is truly inspiring and you are a great role model for a lot of people and we love you so much</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!newrelease</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Curlie hasn't played enough games yet with the newly released pokemon to formulate a proper opinion on it. She goes into these new releases blind so she can give us a more natural reaction to it.</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!newsub</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">curlieqUwu 100% authentic curlieqEspeon grass-fed curlieqHappi cage-free curlieqCynda all-natural curlieqGrowlithe new sub curlieqSprigatito</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!newvid</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Curlie has a new video up on YouTube! Check out "TOTK Shrines & Ground Exploring vod ep.02" -> https://www.youtube.com/watch?v=-3suO_CH6y8 curlieqLurk</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!normal</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Fighting</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!number1</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">psykey number one absol NA</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!nuzlockenames</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">When a Pokémon is captured, if you're subscribed, you can request a nickname. First come, first served. No reserving names.</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!nymble</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">curlieqKricketune THIS IS curlieqRaichu A KRICKETUNE ONLY curlieqRaichu curlieqRaichu SPACE curlieqKricketune</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!oops</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">/me oopsie doopsie froogyLUL </td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!organism</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">@OrganismZero!! Come quickly!! We broke something!!!</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!ornament</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Want to get an ornament on Curlie’s tree? It’s super easy, a tier 1 (re)sub OR a gifted sub will get your name on an energy card of your choice! Want something with a little more pizzazz? A tier 2 or 3 sub will get your name on a Pokémon card of your choice: https://docs.google.com/spreadsheets/d/1O9wAztuLm69rKdMVMAizEosl7N9Zop3nenMo44fvvuc/edit?usp=sharing. Limit one per person.</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!partner</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Your princess is in another castle. Curlie already has a partner, she's a Twitch Partner! SylveonRip</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!patchnotes</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">https://www.pokemonunite.jp/ja/news/143/</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!penta</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">CurlieQuad aha</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!piplup</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">piplupStep we piplupStep demand piplupStep PIPLUP piplupStep</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!plants</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">🌱 Parlor Palm (Chamaedorea elegans) 🌱 Pink Lady Turtle Vine (Callisia repens 'Pink Lady') 🌱 Satin Pothos 'Argyraeus' (Scindapsus pictus 'Argyraeus') 🌱 Swiss Cheese Plant (Monstera adansonii) 🌱</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!playlist</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">https://open.spotify.com/playlist/41K93xoyW332QGAhnDJtXB?si=81982fa16ffc4bc0</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!podcaststream</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">This is a short podcast stream! Thank you so much for watching. Please be aware that this is a different kind of stream and Curlie has to keep her focus on the podcast. She sees you and appreciates you for hanging out. Enjoy! <3</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!pog</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">/me She's doing it!! curlieqPog</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!poggers</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">curlieqPog She did it!! curlieqPog</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!poison</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Ground, Psychic</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!politics</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">/me We like to keep chat lighthearted and fun. Please do not discuss politics here. lets keep it positive!</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!potion</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">I don’t always use my potion… but when I do… I didn’t mean to</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!president</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">curlie has been streaming for as long as a u.s. presidential term i think that makes her qualified to qast</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!prime</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">/me PrimeMe Subscribe for free by linking Twitch Prime btw TPFufun PrimeMe https://twitch.amazon.com/tp</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!proposal</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">The story of how it happened -> https://www.twitch.tv/videos/2151196319 curlieqLove</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!psychic</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Bug, Dark, Ghost</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!psykey</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">my amazing queen psykey. i can’t talk bad about you. you go have fun and i hope you have a great rest of your day</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!qeilruc</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">yad ruoy fo tser taerg a evah uoy epoh i dna nuf evah og uoy .uoy tuoba dab klat t'nac i .qeilruc neeuq naidanac ym</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!qrew</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">curlieqUwu CurlieQrew4Life! curlieqUwu CurlieQrew4Life! curlieqUwu CurlieQrew4Life! curlieqUwu CurlieQrew4Life! curlieqUwu CurlieQrew4Life! curlieqUwu CurlieQrew4Life! curlieqUwu CurlieQrew4Life! curlieqUwu CurlieQrew4Life! curlieqUwu</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!qrewmates</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Qrewmates is a casual stream team of friends just trying to make goofy content for you! 💛 On Twitch: https://www.twitch.tv/team/Qrewmates 💛 On Twitter: https://twitter.com/qrewmates 💛</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!qult</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">curlieqUwu WE'RE A QULT! curlieqUwu WELCOME TO QURCH! curlieqUwu</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!ralph</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">I'M GONNA WRECK IT</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!ray</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">👏GO👏TO👏RAY👏</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!reddit</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">https://www.reddit.com/r/CurliesQueue/</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!riot</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">curlieqJam We curlieqJam cat curlieqJam we curlieqJam jam curlieqJam no curlieqJam mods curlieqJam no curlieqJam bans curlieqJam</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!rock</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Fighting, Grass, Ground, Steel, Water</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!rotate</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">We're all rotom gamers here</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!rotomgamers</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">1. Dred is DED. Do NOT rotate 2. Dunk for DubZ. Rotom shall lead the way PraiseIt 3. Zap is whack. Rotom in enemy base is Free-lo</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!rules</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">/me Be respectful | Keep chat positive | No self-promoting | No backseat gaming</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!sableye</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">all my homies hate Sableye, Zacian and Mewtwo</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!save</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">SAVE YOUR GAME!!!</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!sayzacian</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Here's how you pronounce "Zacian": https://youtu.be/Qyfyd_t9mzs?t=499 (08:23)</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!scaldbro</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">LETHERSPIT</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!schedule</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Curlie streams every Monday - Friday evening (Mountain Time). For the most reliable stream updates, be sure to join the Curlie Qrew Discord! https://bit.ly/3xjBuO7</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!screen</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">@CurlieQ CHANGE THE SCREEN WE CANT SEE CONTENT!</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!seabass</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">/me It's at least a C+ TriHard</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!secure</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">I AM THE SECURE!!! curlieqDab</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!selfpromo</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">/me Nothing personal but no self-promoting please</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!shaders</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">https://www.bslshaders.com/download/</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!shain</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">i am a fall gay</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!shaindelure</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">CONGRATS! YOU'VE WON NOTHING!</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!sheatethat</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">OrangeChicken AND Lasagna</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!shieldmode</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Chat is temporarily in follower-only mode due to a minor inconvenience and will go back to normal soon! Thank you for your patience and understanding!</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!shieldmodeoff</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Thank you for your patience! Shield mode is now off and chat is back to normal. Enjoy the stream! <3</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!shinies</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Curlie appreciates the gesture but she likes to hunt the shinies herself. It gives replay value to game for her</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!shinyluck</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">shinyLuck may the stars align on this blessed day and bring to our streamer many a shiny adorned with colors and those little symbol things (?) and may she and said shiny live a happy life together shinyLuck</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!shinysammie</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">https://www.reddit.com/r/PokemonScarletViolet/comments/z5257c/updated_chart_for_making_the_perfect_sparkling/</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!silly</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">https://clips.twitch.tv/ElatedPoorMageLitty-XR2yMcOvV6PBWowW</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!sinnoh</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">CurlieQ, Champion 🏆 of Sinnoh. Her 👄 reign will ☠️ be 🧐❤️ just 🏚️ and fair. 😆 Today, 📆 she 😡👁️😷 ate 🍲😋 like 😍💋 Eve 🎄❗ did 😳 in 😩 the Garden 🌻 of Eden, 😨🍎🏀 like 👍 Matilda did 😳 to Mrs. 🤶 Trunchbull's cake, ➰🍰🍰❓📦🍥👩‍👩‍👧‍👦♿ like 👩‍❤️‍👩💏 Onika and her 🙄🙄🧐 burgers. She 🧏 served, 😍🌺✨🌈 she 💁‍♀️ mothered, she 🙋‍♀️ saw, 👀👁️😮 she 👩🏽 conquered. 🤴 All ☀️🔥🌅🌄 hail Champion 🏆 Curlie!</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!slay</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">CURLIE ITS ME PSYKEY TELLING YOU THAT NO MATTER WHAT YOU BETTER WORK!!! IDC!!! YOU 1V5 YOU STRUT UR STUFF YOU DO THE BEST U CAN WITH WHAT U GOT AND UR BEST IS ALWAYS GOOD ENOUGH U GOT THIS MAMA SLAY HARDER I DARE YOU</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!slay2</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">HEY 5 STACK IT'S ME ALDWIN TELLING YOU THAT NO MATTER WHAT YOU BETTER WORK!!! IDC!!! YOU EXECUTE GUILLOTINE STYLE YOU STRUT UR STUFF YOU DO THE BEST U CAN WITH WHAT U GOT AND UR BEST IS ALWAYS GOOD ENOUGH U GOT THIS BADDIES SLAY HARDER I DARE YOU</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!slouch</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Curlie! Stop slouching! You’ll ruin your posture young lady! curlieqRaichu</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!snac</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;"> peepoBlushCoffee peepoBlushCoffee peepoPopcorn peepoPopcorn peepoBlushCoffee peepoBlushCoffee peepoPopcorn peepoPopcorn peepoBlushCoffee peepoBlushCoffee peepoPopcorn peepoPopcorn  peepoBlushCoffee peepoBlushCoffee peepoPopcorn peepoPopcorn peepoBlushCoffee peepoBlushCoffee peepoPopcorn peepoPopcorn peepoBlushCoffee peepoBlushCoffee peepoPopcorn peepoPopcorn  peepoBlushCoffee peepoBlushCoffee peepoPopcorn peepoPopcorn peepoBlushCoffee peepoBlushCoffee peepoPopcorn</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!sneeze</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">peepoBless geshundheit peepoBless blessings to you peepoBless and your family peepoBless</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!sniper</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">  piplupHmph sniper no sniping  piplupHmph</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!sniping</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">https://youtu.be/l60MnDJklnM</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!socials</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">/me Find all of Curlie's socials and affiliate links right here:   https://curlieq.live/</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!song</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">It's THE SONG!!! dittoPride DANCE dittoPride DANCE dittoPride DANCE dittoPride DANCE dittoPride DANCE dittoPride DANCE dittoPride DANCE dittoPride DANCE dittoPride DANCE dittoPride DANCE dittoPride DANCE dittoPride DANCE dittoPride DANCE dittoPride DANCE dittoPride DANCE dittoPride DANCE dittoPride DANCE dittoPride DANCE dittoPride DANCE dittoPride DANCE</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!sorry</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Oohh, I'm so sorry I outsecured you. Git gud, I guess? curlieqZorua</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!sparrot</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">🤚 🧿 👄 🧿 🤚</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!spoilers</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Please allow Curlie to discover all the game has to offer in her own time curlieqDed</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!squad</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">https://www.twitch.tv/curlieq/squad</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!sraid</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">curlieqLove CurlieQrew Chooses YOU! curlieqChonka CurlieQrew Chooses YOU! curlieqLove</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!steel</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Fire, Fighting, Ground</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!stinky</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">stinky, 🦨 our 💨🍔 goat. ♑ the cricket, 🦗 the mythic, the legendary. stinky 💩 will 💫🌸🧚🏻 go ❤️ down ⬇️ in 😈 history 🚫 as one 📷 of the greatests of all 💯 time. 🕐 how 😮 many 👬 letters 🔠 in 💗🏡 kricketune? 10. 🔟 how 😐 many ❔ letters 🔤 in 👉👏 stinky? 💩 6. ❓ what's 🆙 10-6? 4. ⛳ what's 🆙 4+4? 🧎‍♀️ 8. 💜 and that 👉👉👉 he 👨 did. 😼 stinky 💩 ate. 🍲😋</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!strike</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">curlieqUwu WE STRIKE AT DAWN curlieqUwu curlieqUwu WE STRIKE AT DAWN curlieqUwu curlieqUwu WE STRIKE AT DAWN curlieqUwu curlieqUwu WE STRIKE AT DAWN curlieqUwu curlieqUwu WE STRIKE AT DAWN curlieqUwu</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!subperks</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">/me Are you REALLY enjoying the content? Consider subscribing to help support the stream even more! With your sub you get access to 30+ exclusive emotes | AD free viewing | Special Sub Role in the discord - Access to Movie Nights & Bonus Discord Streams. https://www.twitch.tv/subs/CurlieQ</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!sucks</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Sucks to suck curlieqRip</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!survive</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Best way to survive is to not die</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!survivors</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">If you would like to make a contribution to survivors.org, victims of abuse, please donate at https://events.softgiving.com/donate/CurlieQForSurvivors</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!teraraids</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">These Tera raids have boosted odds of dropping an Herba Mystica 5-STAR: Gengar, Blissey, Glalie, Drifblim, Amoongus, Eelektross, Dondozo, Palafin, Cetitan. 6-STAR: Vaporeon, Blissey, Amoongus, Farigarif, Dondozo, Cetitan.</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!texturepack</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">This texture pack is currently a work in progress but you can get access and help support the creator at www.patreon.com/MagicTexturePack</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!thanks</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Thanks! Thanks! Thanks! Thanks! Thanks!</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!threat</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">lonkWalk you are SHOWING threatening BEHAVIOR lonkWalk</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!throne</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Thanks to Throne, you can surprise Curlie with a gift from her own private wishlist! All gifts are intended to contribute to the stream in some way, whether it be equipment or aesthetics. Check out her Wish List right here: thrn.co/u/curlieq</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!tiktok</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">https://www.tiktok.com/@curlieqgamer I don't post here often though and I don't like using this app :)</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!twd</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">i wonder if anyone's home. i'd fill one of those teacups up with bourbon if i could. there's no way i can get up there, not with this leg anyway</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!tweezers</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">If tweezers has million number of fans i am one of them . if tweezers has ten fans i am one of them. if tweezers have only one fan and that is me . if tweezers has no fans, that means i am no more on the earth . if world against the tweezers, i am against the world. i love #tweezers till my last breath.. .. Die Hard fan of tweezers . Hit Like If you Think tweezers Best tweezer & Smart In the world</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!twitter</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Follow Curlie off stream on twitter to keep up with important announcements, updates, useless information, and memes: https://twitter.com/CurlieQgamer</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!ugly</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">@${user} Always 0%! You're a beautiful and unique snowflake, just like all the other chatters! curlieqLove</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!ult</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Ackchyually it’s called a Unite Move</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!uniteapi</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">https://uniteapi.dev/p/K0T01M8</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!uniteid</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">K0T01M8</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!upupdowndownleftrightleftrightab</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">curlieqPog GOD MODE UNLOCKED! curlieqPog</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!vent</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">LET HER VENT curlieqRowlet</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!viewergames</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Curlie sometimes hosts viewer game streams on Fridays. Other streams Curlie may SoloQ or pre-arrange teammates. It’s all fun! curlieqLax</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!voibs</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">you know them curlieqMurder</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!vraid</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;"><3 Curlie Qrew Chooses YOU! <3 Curlie Qrew Chooses YOU! <3 </td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!warning</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">You are trying to score here? Nah fam, this place is protected by the most holy and curlie of the Qs. Only those who dare to tempt fate come across such jacked and cracked player; you know it to be true. Take one more step and you will feel the wrath and fury that puts even the most feared gods to shame. Now that you have been warned be ready to face the unmovable, unbreakable, and unstoppable player in the game.</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!water</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Electric, Grass</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!welcome</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">curlieqWave Welcome to the Curlie Qrew! Curlie streams a range of games! Catch her live every M-F! Be sure to click that follow button if you're enjoying the content to be notified for future streams. If you'd like to find Curlie elsewhere on the internet here are all her links: https://curlieq.live/ Feel free to reach out to the mods if you have any questions. Thank you for supporting the stream, enjoy your stay! curlieqSwinub</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!wheel</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Our list of wheel comps for Pokémon Unite is here: https://docs.google.com/spreadsheets/d/1zxwP_oplyg5rO9t4WGc38hku3FvZlWuSEimalEz2mOg/edit?usp=sharing</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!wobbuffet</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">curlieqWobbuffet curlieqWobbuffet curlieqWobbuffet</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!yall</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">https://www.youtube.com/watch?v=ilu6HyawOL0</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!yekysp</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">yad ruoy fo tser taerg a evah uoy epoh i dna nuf evah og uoy .uoy tuoba dab klat t'nac i .yekysp neeuq gnizama ym</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!youtube</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Curlie is on her way to Youtube Partner!! Be sure to check out her channel here and don't forget to subscribe! https://www.youtube.com/@CurlieQ?sub_confirmation=1</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!zacianemblem</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Steps to get this to avoid confusion: 1. Make sure your twitch is connected to your pokemon trainer club account 2. Watch the stream for 30 minutes, this will then let you claim the reward on twitch 3. Go to rewards.pokemon .com, login to your account and view your inventory. Your code should be there and ofc use it in the gift exchange in unite to claim it in game. Hope this helps!</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!ziggy</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">imagine being a cis het male and being so unbalievably wrong. It's more likely than you'd think</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>

  <tr>
    <td title="&nbsp;" style="font-family: monospace; width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">!zoroark</td>
    <td style="width: 65%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">zaw · row · aark</td>
    <td style="width: 15%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Viewer</td>
    <td style="width: 10%; max-width: 0; overflow: hidden; text-overflow: ellipsis; white-space: normal; overflow: hidden; border-top: 1px rgba(0, 0, 0, 0.12) solid; border-left: 1px rgba(0, 0, 0, 0.12) solid; overflow-wrap: normal;">Yes</td>
  </tr>


</table>


<p>Made with ❤ by OrganismZero</p>
