# adventOfCode template

This repo is intended to be forked for each new year for Advent Of Code (https://adventofcode.com)

# CLI option

You can run by star, or by day

 <code>node adventOfCode.js star1</code> <br />
 <code>node adventOfCode.js day1</code>


To generate the infrastructure needed run the next star in the sequence, you can run:
<code>node adventOfCode.js generatestar</code> which will automatically create the file for the next star, as well as set up the plumbing needed to run that star via the commands above.

For example, if you just finished completing star6 (2nd star of day3), executing the `generatestar` command it will automatically create a folder for day4, as well as star7.js in that folder, and all the plubming necessary such that you could run <code>node adventOfCode.js star7</code>.
