# Discord-Code-Execution
This is just a simple exploit to run code under the Discord process. \
Discord does not check the integrity of the files, which allows an attacker to add whatever code they please. \
Discord is aware of this issue, but refuse to fix it, so might as well put it here.

Note, I'm not claiming to be the original author of this exploit, it was found by some unknown malware dev. \
But since i haven't been able to find any code examples of it, or a CVE, i put one together myself.

It works on both Windows and Linux


# Usage
Nothing fancy here, you just run it with python3, and if you want to revert back to the original file, you add "restore".

# TODO
- [ ] Add multiple payloads/a menu to select which payload
- [ ] Create more tools using this
