alias autofire_on "alias spam_loop spam; spam; bind MOUSE3 autofire_off; echo AutoFire ON"
alias autofire_off "alias spam_loop; -attack; bind MOUSE3 autofire_on; echo AutoFire OFF"
alias spam "+attack; wait 1; -attack; wait 1; spam_loop"
alias spam_loop "spam"

bind MOUSE3 autofire_on

// This confirms Fast fire Script is active
echo
echo
echo ! ! ! ! ! Fast Fire Script is active ! ! ! ! !
echo
echo ! ! ! ! ! Fast Fire Script is active ! ! ! ! !
echo
echo ! ! ! ! ! 300FPS ! ! ! ! !
echo
