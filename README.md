# Repo1
[17:43:54.483] Running build in Washington, D.C., USA (East) – iad1
[17:43:54.484] Build machine configuration: 2 cores, 8 GB
[17:43:54.497] Cloning github.com/Liwandowski9/codespaces-react (Branch: main, Commit: ccb1849)
[17:43:54.513] Skipping build cache, deployment was triggered without cache.
[17:43:54.780] Cloning completed: 283.000ms
[17:43:55.076] Running "vercel build"
[17:43:56.118] Vercel CLI 44.4.3
[17:43:57.752] Installing dependencies...
[17:44:01.967] 
[17:44:01.968] added 295 packages in 4s
[17:44:01.969] 
[17:44:01.969] 61 packages are looking for funding
[17:44:01.969]   run `npm fund` for details
[17:44:02.010] Running "npm run build"
[17:44:02.121] 
[17:44:02.121] > codespaces-react@0.1.0 build
[17:44:02.121] > vite build
[17:44:02.122] 
[17:44:02.525] [36mvite v4.5.9 [32mbuilding for production...[36m[39m
[17:44:02.570] transforming...
[17:44:02.614] [32m✓[39m 5 modules transformed.
[17:44:02.615] [32m✓ built in 88ms[39m
[17:44:02.615] [31m[vite:esbuild] Transform failed with 1 error:
[17:44:02.615] /vercel/path0/src/App.jsx:31:29: ERROR: Expected "}" but found "Question"[39m
[17:44:02.615] file: [36m/vercel/path0/src/App.jsx:31:29[39m
[17:44:02.615] [33m
[17:44:02.616] [33mExpected "}" but found "Question"[33m
[17:44:02.616] 29 |  export default App;
[17:44:02.616] 30 |  import { useState, useMemo, useEffect } from 'react';
[17:44:02.616] 31 |  import { quizQuestions, type Question } from '@/lib/quiz-data';
[17:44:02.616]    |                               ^
[17:44:02.616] 32 |  import { Button } from '@/components/ui/button';
[17:44:02.616] 33 |  import { Card, CardContent, CardHeader, CardTitle, CardDescription } from '@/components/ui/card';
[17:44:02.616] [39m
[17:44:02.616] [31merror during build:
[17:44:02.616] Error: Transform failed with 1 error:
[17:44:02.616] /vercel/path0/src/App.jsx:31:29: ERROR: Expected "}" but found "Question"
[17:44:02.617]     at failureErrorWithLog (/vercel/path0/node_modules/esbuild/lib/main.js:1649:15)
[17:44:02.617]     at /vercel/path0/node_modules/esbuild/lib/main.js:847:29
[17:44:02.617]     at responseCallbacks.<computed> (/vercel/path0/node_modules/esbuild/lib/main.js:703:9)
[17:44:02.617]     at handleIncomingPacket (/vercel/path0/node_modules/esbuild/lib/main.js:762:9)
[17:44:02.617]     at Socket.readFromStdout (/vercel/path0/node_modules/esbuild/lib/main.js:679:7)
[17:44:02.617]     at Socket.emit (node:events:518:28)
[17:44:02.617]     at addChunk (node:internal/streams/readable:561:12)
[17:44:02.617]     at readableAddChunkPushByteMode (node:internal/streams/readable:512:3)
[17:44:02.617]     at Readable.push (node:internal/streams/readable:392:5)
[17:44:02.617]     at Pipe.onStreamRead (node:internal/stream_base_commons:189:23)[39m
[17:44:02.637] Error: Command "npm run build" exited with 1
[17:44:02.797] g.j