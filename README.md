meteor-issue-662
================

Demonstration and some tests for Meteor's issue #662 (meteor/meteor#662).

Steps to reproduce:
1. `https://github.com/yeputons/meteor-issue-662.git`.
2. `cd meteor-issue-662`
3. `meteor`
4. Open `http://localhost:3000` and ensure that five 'Fancy' blocks have fancy font,
   and two 'Standard' blocks have standard font
5. `meteor --production`
5. Open `http://localhost:3000`, behavior differs.

File `extra.css` is not required for bug, you can freely remove it.
