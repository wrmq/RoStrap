RoStrap - Read Me First
========================

Read this in full before you install or run RoStrap.exe. It's long on purpose - this is the
actual terms you're agreeing to, not filler.


WHAT THIS IS
------------
RoStrap is an independent, third-party Roblox bootstrapper. It manages your Roblox install and,
on every launch, writes FastFlag configuration values into Roblox's own ClientAppSettings.json
mechanism - the same general approach used by other public Roblox bootstrappers. It does not
patch Roblox's binaries, inject code into its process, or modify game logic at runtime.


NOT AFFILIATED WITH ROBLOX CORPORATION
---------------------------------------
RoStrap is not created by, endorsed by, sponsored by, or in any way officially connected with
Roblox Corporation or any of its subsidiaries or affiliates. "Roblox" and all related trademarks
are the property of Roblox Corporation. Any mention of Roblox here is purely descriptive, to
explain what this tool interacts with.


YOU ARE SOLELY RESPONSIBLE FOR HOW YOU USE THIS
-------------------------------------------------
Changing FastFlags still means running the Roblox client in a configuration Roblox did not ship
by default and does not officially document or support for third-party use. FastFlags - including
any you add yourself from community lists, other users, or anywhere else - can range from purely
cosmetic (disabling shadows, uncapping FPS) to flags that materially change gameplay behavior,
expose information, or otherwise cross into territory Roblox could reasonably classify as
exploiting, cheating, or violating its Terms of Use, Community Standards, or Developer Terms.

RoStrap does not curate, vet, endorse, or take responsibility for the effect of any specific flag,
value, or combination of flags. Whether a given flag is "safe," cosmetic, or something Roblox
would consider abuse is entirely on you to research and judge before you set it.

The author of this software:

  - Does NOT encourage, condone, or endorse using RoStrap, or any FastFlag configuration, to
    cheat, exploit, gain an unfair advantage, harass other players, circumvent moderation, or
    otherwise violate Roblox's Terms of Use, Community Standards, or any applicable law.

  - Is NOT LIABLE for any consequence arising from how you, or anyone else, configures or uses
    this software - including but not limited to account warnings, suspensions, permanent bans,
    termination, or loss of access to purchased items, Robux, Premium subscriptions, or any other
    virtual or real-world property or currency, whether that consequence comes from Roblox
    Corporation, another player, or any third party.

  - Provides this software purely as a general-purpose configuration and launch tool and takes no
    responsibility for actions taken by third parties using it.


USE AT YOUR OWN RISK
----------------------
Everything about running RoStrap - installing it, configuring FastFlags through it, using its
Discord Rich Presence integration, registering it as your roblox-player: link handler, or
anything else it does - is done entirely at your own risk and your own discretion. This includes,
but is not limited to, the risk of:

  - Roblox account action, up to and including permanent termination
  - Loss of in-game or account progress, purchases, or items
  - Roblox client updates breaking FastFlags or installation without notice (Roblox renames and
    retires flags between updates with no obligation to tell anyone)
  - Any bugs, data loss, or unintended behavior in RoStrap itself


NO WARRANTY OF ANY KIND
--------------------------
RoStrap is provided "AS IS" and "AS AVAILABLE," without warranty of any kind, express or implied,
including but not limited to warranties of merchantability, fitness for a particular purpose,
non-infringement, accuracy, or that the software will be uninterrupted, error-free, secure, or
compatible with any particular version of the Roblox client. Roblox can change its client, its
FastFlag system, its Terms of Use, or its enforcement practices at any time without notice, and
nothing here guarantees RoStrap will continue to work, or continue to be tolerated, after any such
change.


LIMITATION OF LIABILITY
--------------------------
To the fullest extent permitted by applicable law, in no event will the author(s) or copyright
holder(s) of RoStrap be liable for any direct, indirect, incidental, special, consequential,
exemplary, or punitive damages whatsoever - including but not limited to damages for loss of
accounts, data, goodwill, profits, or other intangible losses - arising out of or in connection
with your access to, download of, installation of, or use of (or inability to use) this software,
however caused and under any theory of liability (contract, tort, negligence, or otherwise), even
if advised of the possibility of such damages.


YOU ACCEPT THESE TERMS BY USING THIS PROGRAM
-----------------------------------------------
By downloading, installing, launching, or otherwise using RoStrap in any way, you acknowledge
that you have read and understood this entire document, and you agree to be bound by it and to
assume full personal responsibility for your own compliance with Roblox's Terms of Use, Community
Standards, Developer Terms, and any applicable law.

This acceptance is AUTOMATIC and applies the moment you use the software in any capacity - there
is no separate opt-in step, and running RoStrap.exe after reading this constitutes your agreement.

If you do not agree to these terms, you must not install or run RoStrap, and you should delete
any copies of it in your possession.


NO SUPPORT OR CONTINUITY GUARANTEE
-------------------------------------
This document, and the software itself, may be updated, changed, or discontinued at any time
without notice. Nothing here obligates the author to provide support, updates, bug fixes, or
continued availability of RoStrap in any form.


WHERE YOUR DATA LIVES
------------------------
Settings are stored locally at:  %LOCALAPPDATA%\RoStrap\settings.json
The Roblox install itself lives at:  %LOCALAPPDATA%\RoStrap\Versions (by default, changeable in
the app's Bootstrapper page)

RoStrap does not send your settings or activity to the author or any third party beyond what
Discord Rich Presence itself requires when that feature is enabled (i.e. talking to your local
Discord client).
