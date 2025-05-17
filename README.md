Required Software Versions
Node.js version: v24.0.02 
MongoDB version: v8.0.9
Nats-Server version: v2.11.3
Nats-CLI version: v0.2.3
OS version: Ubuntu v24.04 

Check the respective software sites for installation pages on how to get them up and running.


Steps To Get Started
1. Clone The Repository. Use the following command:
`git clone --recurse-submodules git@github.com:Acchu07/KoinX_Assignment.git`
2. Check the readmes of the respective folders on how to run the respective applications


FAQ

1. Why Current Node.js Version and Not LTS?

I chose the Current Node.js version because it has better native TypeScript support than LTS, reducing setup time and debugging—close to Deno.

2. Why not Hono instead of Express?

Hono may be more optimal, but I chose Express because I'm already familiar with it. Since TypeScript is new to me, I wanted to avoid adding extra complexity.

3. Docker?

Might Update with Docker Files - TBD

4. Why TypeScript? Couldn't You Have Completed it faster if you built it with just Javascript

Yes, JavaScript would be faster, but I prefer TypeScript for compile-time checks and static typing. Beyond preference, it's a valuable skill, and I'm building familiarity early.




