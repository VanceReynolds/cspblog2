---
toc: true
comments: true
layout: post
title: Problems V1
description: Originally on home page for tools check. Includes week 0.
type: tangibles
courses: { compsci: {week: 1} }
---
## My Strugles

- The first major issue I encountered was with my WSL. Although WSL was installed, PowerShell would not recognize it. This occurred because there was a preexisting version of WSL on my device that was likely outdated. As a result, I decided to uninstall WSL and Ubuntu, and then I had to redo all the progress I had made up to that point.

- Another problem I had was that my website was not accessible. When I ran "make" in my VSCode, it would generate a link to my page, but I couldn't view it. I spent hours troubleshooting this issue and eventually found a post on GitHub by someone who had a similar problem. They resolved the issue by changing their address to a more direct one, using "127.0.0.1" instead of "0.0.0.0". Additionally, I installed "ng common" and ran a server, which fixed my problem and allowed me to access my website.

- After getting my website up and running and editing its appearance, I found that I didn't have the ability to commit to my repository. This could have been caused by a number of different issues. However, with Mr. Mortenson's help, the problem was resolved by installing extensions like Remote SSH and its components.