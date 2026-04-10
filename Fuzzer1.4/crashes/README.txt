Command line used to find this crash:

./afl-fuzz -K ./gui_utils/atspi_clicks.py -t 100000 -i in -o out -m none -- /usr/bin/krita --nosplash --template /home/vboxuser/Pictures/template.kra

If you can't reproduce a bug outside of afl-fuzz, be sure to set the same
memory limit. The limit used for this fuzzing session was 0 B.

Need a tool to minimize test cases before investigating the crashes or sending
them to a vendor? Check out the afl-tmin that comes with the fuzzer!

Found any cool bugs in open-source tools using afl-fuzz? If yes, please post
to https://github.com/AFLplusplus/AFLplusplus/issues/286 once the issues
 are fixed :)

