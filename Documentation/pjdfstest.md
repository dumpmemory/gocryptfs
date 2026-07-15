# How to run

	$ sudo gocryptfs --allow_other a b 
	$ cd b
	$ sudo prove -r /home/jakob/code/pjdfstest/test

# Version Info

https://github.com/pjd/pjdfstest @ 8a2adf0

	$ gocryptfs --version
	gocryptfs v2.6.1-46-gf76f8a2a; go-fuse v2.9.0; 2026-07-15 go1.25.4 linux/amd64

# Results

```
root@brikett:/var/tmp/g/b# prove -r /home/jakob/code/pjdfstest/tests
/home/jakob/code/pjdfstest/tests/chflags/00.t .......... ok   
/home/jakob/code/pjdfstest/tests/chflags/01.t .......... ok   
/home/jakob/code/pjdfstest/tests/chflags/02.t .......... ok   
/home/jakob/code/pjdfstest/tests/chflags/03.t .......... ok   
/home/jakob/code/pjdfstest/tests/chflags/04.t .......... ok   
/home/jakob/code/pjdfstest/tests/chflags/05.t .......... ok   
/home/jakob/code/pjdfstest/tests/chflags/06.t .......... ok   
/home/jakob/code/pjdfstest/tests/chflags/07.t .......... ok   
/home/jakob/code/pjdfstest/tests/chflags/08.t .......... ok   
/home/jakob/code/pjdfstest/tests/chflags/09.t .......... ok   
/home/jakob/code/pjdfstest/tests/chflags/10.t .......... ok   
/home/jakob/code/pjdfstest/tests/chflags/11.t .......... ok   
/home/jakob/code/pjdfstest/tests/chflags/12.t .......... ok   
/home/jakob/code/pjdfstest/tests/chflags/13.t .......... ok   
/home/jakob/code/pjdfstest/tests/chmod/00.t ............ ok       
/home/jakob/code/pjdfstest/tests/chmod/01.t ............ ok     
/home/jakob/code/pjdfstest/tests/chmod/02.t ............ ok   
/home/jakob/code/pjdfstest/tests/chmod/03.t ............ ok   
/home/jakob/code/pjdfstest/tests/chmod/04.t ............ ok   
/home/jakob/code/pjdfstest/tests/chmod/05.t ............ ok     
/home/jakob/code/pjdfstest/tests/chmod/06.t ............ ok   
/home/jakob/code/pjdfstest/tests/chmod/07.t ............ ok     
/home/jakob/code/pjdfstest/tests/chmod/08.t ............ ok   
/home/jakob/code/pjdfstest/tests/chmod/09.t ............ ok   
/home/jakob/code/pjdfstest/tests/chmod/10.t ............ ok   
/home/jakob/code/pjdfstest/tests/chmod/11.t ............ ok       
/home/jakob/code/pjdfstest/tests/chmod/12.t ............ ok     
/home/jakob/code/pjdfstest/tests/chown/00.t ............ ok         
/home/jakob/code/pjdfstest/tests/chown/01.t ............ ok     
/home/jakob/code/pjdfstest/tests/chown/02.t ............ ok     
/home/jakob/code/pjdfstest/tests/chown/03.t ............ ok     
/home/jakob/code/pjdfstest/tests/chown/04.t ............ ok   
/home/jakob/code/pjdfstest/tests/chown/05.t ............ ok     
/home/jakob/code/pjdfstest/tests/chown/06.t ............ ok     
/home/jakob/code/pjdfstest/tests/chown/07.t ............ ok       
/home/jakob/code/pjdfstest/tests/chown/08.t ............ ok   
/home/jakob/code/pjdfstest/tests/chown/09.t ............ ok   
/home/jakob/code/pjdfstest/tests/chown/10.t ............ ok   
/home/jakob/code/pjdfstest/tests/ftruncate/00.t ........ ok     
/home/jakob/code/pjdfstest/tests/ftruncate/01.t ........ ok   
/home/jakob/code/pjdfstest/tests/ftruncate/02.t ........ ok   
/home/jakob/code/pjdfstest/tests/ftruncate/03.t ........ ok   
/home/jakob/code/pjdfstest/tests/ftruncate/04.t ........ ok   
/home/jakob/code/pjdfstest/tests/ftruncate/05.t ........ ok     
/home/jakob/code/pjdfstest/tests/ftruncate/06.t ........ ok   
/home/jakob/code/pjdfstest/tests/ftruncate/07.t ........ ok   
/home/jakob/code/pjdfstest/tests/ftruncate/08.t ........ ok   
/home/jakob/code/pjdfstest/tests/ftruncate/09.t ........ ok   
/home/jakob/code/pjdfstest/tests/ftruncate/10.t ........ ok   
/home/jakob/code/pjdfstest/tests/ftruncate/11.t ........ ok   
/home/jakob/code/pjdfstest/tests/ftruncate/12.t ........ ok   
/home/jakob/code/pjdfstest/tests/ftruncate/13.t ........ ok   
/home/jakob/code/pjdfstest/tests/ftruncate/14.t ........ ok   
/home/jakob/code/pjdfstest/tests/granular/00.t ......... ok   
/home/jakob/code/pjdfstest/tests/granular/01.t ......... ok   
/home/jakob/code/pjdfstest/tests/granular/02.t ......... ok   
/home/jakob/code/pjdfstest/tests/granular/03.t ......... ok   
/home/jakob/code/pjdfstest/tests/granular/04.t ......... ok   
/home/jakob/code/pjdfstest/tests/granular/05.t ......... ok   
/home/jakob/code/pjdfstest/tests/granular/06.t ......... ok   
/home/jakob/code/pjdfstest/tests/link/00.t ............. ok       
/home/jakob/code/pjdfstest/tests/link/01.t ............. ok     
/home/jakob/code/pjdfstest/tests/link/02.t ............. ok     
/home/jakob/code/pjdfstest/tests/link/03.t ............. ok     
/home/jakob/code/pjdfstest/tests/link/04.t ............. ok   
/home/jakob/code/pjdfstest/tests/link/05.t ............. ok   
/home/jakob/code/pjdfstest/tests/link/06.t ............. ok     
/home/jakob/code/pjdfstest/tests/link/07.t ............. ok     
/home/jakob/code/pjdfstest/tests/link/08.t ............. ok     
/home/jakob/code/pjdfstest/tests/link/09.t ............. ok   
/home/jakob/code/pjdfstest/tests/link/10.t ............. ok     
/home/jakob/code/pjdfstest/tests/link/11.t ............. ok   
/home/jakob/code/pjdfstest/tests/link/12.t ............. ok   
/home/jakob/code/pjdfstest/tests/link/13.t ............. ok   
/home/jakob/code/pjdfstest/tests/link/14.t ............. ok   
/home/jakob/code/pjdfstest/tests/link/15.t ............. ok   
/home/jakob/code/pjdfstest/tests/link/16.t ............. ok   
/home/jakob/code/pjdfstest/tests/link/17.t ............. ok   
/home/jakob/code/pjdfstest/tests/mkdir/00.t ............ ok     
/home/jakob/code/pjdfstest/tests/mkdir/01.t ............ ok     
/home/jakob/code/pjdfstest/tests/mkdir/02.t ............ ok   
/home/jakob/code/pjdfstest/tests/mkdir/03.t ............ ok   
/home/jakob/code/pjdfstest/tests/mkdir/04.t ............ ok   
/home/jakob/code/pjdfstest/tests/mkdir/05.t ............ ok     
/home/jakob/code/pjdfstest/tests/mkdir/06.t ............ ok     
/home/jakob/code/pjdfstest/tests/mkdir/07.t ............ ok   
/home/jakob/code/pjdfstest/tests/mkdir/08.t ............ ok   
/home/jakob/code/pjdfstest/tests/mkdir/09.t ............ ok   
/home/jakob/code/pjdfstest/tests/mkdir/10.t ............ ok     
/home/jakob/code/pjdfstest/tests/mkdir/11.t ............ ok   
/home/jakob/code/pjdfstest/tests/mkdir/12.t ............ ok   
/home/jakob/code/pjdfstest/tests/mkfifo/00.t ........... ok     
/home/jakob/code/pjdfstest/tests/mkfifo/01.t ........... ok     
/home/jakob/code/pjdfstest/tests/mkfifo/02.t ........... ok   
/home/jakob/code/pjdfstest/tests/mkfifo/03.t ........... ok   
/home/jakob/code/pjdfstest/tests/mkfifo/04.t ........... ok   
/home/jakob/code/pjdfstest/tests/mkfifo/05.t ........... ok     
/home/jakob/code/pjdfstest/tests/mkfifo/06.t ........... ok     
/home/jakob/code/pjdfstest/tests/mkfifo/07.t ........... ok   
/home/jakob/code/pjdfstest/tests/mkfifo/08.t ........... ok   
/home/jakob/code/pjdfstest/tests/mkfifo/09.t ........... ok     
/home/jakob/code/pjdfstest/tests/mkfifo/10.t ........... ok   
/home/jakob/code/pjdfstest/tests/mkfifo/11.t ........... ok   
/home/jakob/code/pjdfstest/tests/mkfifo/12.t ........... ok   
/home/jakob/code/pjdfstest/tests/mknod/00.t ............ ok     
/home/jakob/code/pjdfstest/tests/mknod/01.t ............ ok     
/home/jakob/code/pjdfstest/tests/mknod/02.t ............ ok     
/home/jakob/code/pjdfstest/tests/mknod/03.t ............ ok     
/home/jakob/code/pjdfstest/tests/mknod/04.t ............ ok   
/home/jakob/code/pjdfstest/tests/mknod/05.t ............ ok     
/home/jakob/code/pjdfstest/tests/mknod/06.t ............ ok     
/home/jakob/code/pjdfstest/tests/mknod/07.t ............ ok   
/home/jakob/code/pjdfstest/tests/mknod/08.t ............ ok     
/home/jakob/code/pjdfstest/tests/mknod/09.t ............ ok   
/home/jakob/code/pjdfstest/tests/mknod/10.t ............ ok   
/home/jakob/code/pjdfstest/tests/mknod/11.t ............ ok     
/home/jakob/code/pjdfstest/tests/open/00.t ............. ok     
/home/jakob/code/pjdfstest/tests/open/01.t ............. ok     
/home/jakob/code/pjdfstest/tests/open/02.t ............. ok   
/home/jakob/code/pjdfstest/tests/open/03.t ............. ok   
/home/jakob/code/pjdfstest/tests/open/04.t ............. ok   
/home/jakob/code/pjdfstest/tests/open/05.t ............. ok     
/home/jakob/code/pjdfstest/tests/open/06.t ............. ok       
/home/jakob/code/pjdfstest/tests/open/07.t ............. ok     
/home/jakob/code/pjdfstest/tests/open/08.t ............. ok   
/home/jakob/code/pjdfstest/tests/open/09.t ............. ok   
/home/jakob/code/pjdfstest/tests/open/10.t ............. ok   
/home/jakob/code/pjdfstest/tests/open/11.t ............. ok   
/home/jakob/code/pjdfstest/tests/open/12.t ............. ok   
/home/jakob/code/pjdfstest/tests/open/13.t ............. ok   
/home/jakob/code/pjdfstest/tests/open/14.t ............. ok   
/home/jakob/code/pjdfstest/tests/open/15.t ............. ok   
/home/jakob/code/pjdfstest/tests/open/16.t ............. ok   
/home/jakob/code/pjdfstest/tests/open/17.t ............. ok   
/home/jakob/code/pjdfstest/tests/open/18.t ............. ok   
/home/jakob/code/pjdfstest/tests/open/19.t ............. ok   
/home/jakob/code/pjdfstest/tests/open/20.t ............. ok   
/home/jakob/code/pjdfstest/tests/open/21.t ............. ok   
/home/jakob/code/pjdfstest/tests/open/22.t ............. ok     
/home/jakob/code/pjdfstest/tests/open/23.t ............. ok   
/home/jakob/code/pjdfstest/tests/open/24.t ............. ok   
/home/jakob/code/pjdfstest/tests/open/25.t ............. ok   
/home/jakob/code/pjdfstest/tests/posix_fallocate/00.t .. ok   
/home/jakob/code/pjdfstest/tests/rename/00.t ........... ok       
/home/jakob/code/pjdfstest/tests/rename/01.t ........... ok   
/home/jakob/code/pjdfstest/tests/rename/02.t ........... ok   
/home/jakob/code/pjdfstest/tests/rename/03.t ........... ok   
/home/jakob/code/pjdfstest/tests/rename/04.t ........... ok     
/home/jakob/code/pjdfstest/tests/rename/05.t ........... ok     
/home/jakob/code/pjdfstest/tests/rename/06.t ........... ok   
/home/jakob/code/pjdfstest/tests/rename/07.t ........... ok   
/home/jakob/code/pjdfstest/tests/rename/08.t ........... ok   
/home/jakob/code/pjdfstest/tests/rename/09.t ........... ok         
/home/jakob/code/pjdfstest/tests/rename/10.t ........... ok         
/home/jakob/code/pjdfstest/tests/rename/11.t ........... ok     
/home/jakob/code/pjdfstest/tests/rename/12.t ........... ok     
/home/jakob/code/pjdfstest/tests/rename/13.t ........... ok     
/home/jakob/code/pjdfstest/tests/rename/14.t ........... ok     
/home/jakob/code/pjdfstest/tests/rename/15.t ........... ok   
/home/jakob/code/pjdfstest/tests/rename/16.t ........... ok   
/home/jakob/code/pjdfstest/tests/rename/17.t ........... ok   
/home/jakob/code/pjdfstest/tests/rename/18.t ........... ok   
/home/jakob/code/pjdfstest/tests/rename/19.t ........... ok   
/home/jakob/code/pjdfstest/tests/rename/20.t ........... ok     
/home/jakob/code/pjdfstest/tests/rename/21.t ........... ok     
/home/jakob/code/pjdfstest/tests/rename/22.t ........... ok   
/home/jakob/code/pjdfstest/tests/rename/23.t ........... ok     
/home/jakob/code/pjdfstest/tests/rename/24.t ........... ok     
/home/jakob/code/pjdfstest/tests/rmdir/00.t ............ ok     
/home/jakob/code/pjdfstest/tests/rmdir/01.t ............ ok     
/home/jakob/code/pjdfstest/tests/rmdir/02.t ............ ok   
/home/jakob/code/pjdfstest/tests/rmdir/03.t ............ ok   
/home/jakob/code/pjdfstest/tests/rmdir/04.t ............ ok   
/home/jakob/code/pjdfstest/tests/rmdir/05.t ............ ok   
/home/jakob/code/pjdfstest/tests/rmdir/06.t ............ ok     
/home/jakob/code/pjdfstest/tests/rmdir/07.t ............ ok     
/home/jakob/code/pjdfstest/tests/rmdir/08.t ............ ok     
/home/jakob/code/pjdfstest/tests/rmdir/09.t ............ ok   
/home/jakob/code/pjdfstest/tests/rmdir/10.t ............ ok   
/home/jakob/code/pjdfstest/tests/rmdir/11.t ............ ok     
/home/jakob/code/pjdfstest/tests/rmdir/12.t ............ ok   
/home/jakob/code/pjdfstest/tests/rmdir/13.t ............ ok   
/home/jakob/code/pjdfstest/tests/rmdir/14.t ............ ok   
/home/jakob/code/pjdfstest/tests/rmdir/15.t ............ ok   
/home/jakob/code/pjdfstest/tests/symlink/00.t .......... ok     
/home/jakob/code/pjdfstest/tests/symlink/01.t .......... ok   
/home/jakob/code/pjdfstest/tests/symlink/02.t .......... ok   
/home/jakob/code/pjdfstest/tests/symlink/03.t .......... Failed 2/6 subtests 
/home/jakob/code/pjdfstest/tests/symlink/04.t .......... ok   
/home/jakob/code/pjdfstest/tests/symlink/05.t .......... ok     
/home/jakob/code/pjdfstest/tests/symlink/06.t .......... ok     
/home/jakob/code/pjdfstest/tests/symlink/07.t .......... ok   
/home/jakob/code/pjdfstest/tests/symlink/08.t .......... ok     
/home/jakob/code/pjdfstest/tests/symlink/09.t .......... ok   
/home/jakob/code/pjdfstest/tests/symlink/10.t .......... ok   
/home/jakob/code/pjdfstest/tests/symlink/11.t .......... ok   
/home/jakob/code/pjdfstest/tests/symlink/12.t .......... ok   
/home/jakob/code/pjdfstest/tests/truncate/00.t ......... ok     
/home/jakob/code/pjdfstest/tests/truncate/01.t ......... ok   
/home/jakob/code/pjdfstest/tests/truncate/02.t ......... ok   
/home/jakob/code/pjdfstest/tests/truncate/03.t ......... ok   
/home/jakob/code/pjdfstest/tests/truncate/04.t ......... ok   
/home/jakob/code/pjdfstest/tests/truncate/05.t ......... ok     
/home/jakob/code/pjdfstest/tests/truncate/06.t ......... ok   
/home/jakob/code/pjdfstest/tests/truncate/07.t ......... ok   
/home/jakob/code/pjdfstest/tests/truncate/08.t ......... ok   
/home/jakob/code/pjdfstest/tests/truncate/09.t ......... ok   
/home/jakob/code/pjdfstest/tests/truncate/10.t ......... ok   
/home/jakob/code/pjdfstest/tests/truncate/11.t ......... ok   
/home/jakob/code/pjdfstest/tests/truncate/12.t ......... ok   
/home/jakob/code/pjdfstest/tests/truncate/13.t ......... ok   
/home/jakob/code/pjdfstest/tests/truncate/14.t ......... ok   
/home/jakob/code/pjdfstest/tests/unlink/00.t ........... ok       
/home/jakob/code/pjdfstest/tests/unlink/01.t ........... ok   
/home/jakob/code/pjdfstest/tests/unlink/02.t ........... ok   
/home/jakob/code/pjdfstest/tests/unlink/03.t ........... ok   
/home/jakob/code/pjdfstest/tests/unlink/04.t ........... ok   
/home/jakob/code/pjdfstest/tests/unlink/05.t ........... ok     
/home/jakob/code/pjdfstest/tests/unlink/06.t ........... ok     
/home/jakob/code/pjdfstest/tests/unlink/07.t ........... ok   
/home/jakob/code/pjdfstest/tests/unlink/08.t ........... ok   
/home/jakob/code/pjdfstest/tests/unlink/09.t ........... ok   
/home/jakob/code/pjdfstest/tests/unlink/10.t ........... ok   
/home/jakob/code/pjdfstest/tests/unlink/11.t ........... ok       
/home/jakob/code/pjdfstest/tests/unlink/12.t ........... ok   
/home/jakob/code/pjdfstest/tests/unlink/13.t ........... ok   
/home/jakob/code/pjdfstest/tests/unlink/14.t ........... ok   
/home/jakob/code/pjdfstest/tests/utimensat/00.t ........ ok     
/home/jakob/code/pjdfstest/tests/utimensat/01.t ........ ok   
/home/jakob/code/pjdfstest/tests/utimensat/02.t ........ ok     
/home/jakob/code/pjdfstest/tests/utimensat/03.t ........ ok   
/home/jakob/code/pjdfstest/tests/utimensat/04.t ........ ok     
/home/jakob/code/pjdfstest/tests/utimensat/05.t ........ Failed 1/16 subtests 
/home/jakob/code/pjdfstest/tests/utimensat/06.t ........ ok     
/home/jakob/code/pjdfstest/tests/utimensat/07.t ........ ok     
/home/jakob/code/pjdfstest/tests/utimensat/08.t ........ ok   
/home/jakob/code/pjdfstest/tests/utimensat/09.t ........ ok   

Test Summary Report
-------------------
/home/jakob/code/pjdfstest/tests/chown/00.t          (Wstat: 0 Tests: 1280 Failed: 0)
  TODO passed:   1054, 1058, 1064, 1069, 1073, 1079, 1084
                1088, 1094, 1099, 1103, 1109, 1114, 1118
                1124, 1129, 1133, 1139, 1144
/home/jakob/code/pjdfstest/tests/symlink/03.t        (Wstat: 0 Tests: 6 Failed: 2)
  Failed tests:  1-2
/home/jakob/code/pjdfstest/tests/utimensat/05.t      (Wstat: 0 Tests: 16 Failed: 1)
  Failed test:  7
Files=237, Tests=8789, 191 wallclock secs ( 1.80 usr  0.39 sys + 27.57 cusr 36.00 csys = 65.76 CPU)
Result: FAIL
```

# Failure Details

```
root@brikett:/var/tmp/g/b# prove -v /home/jakob/code/pjdfstest/tests/symlink/03.t 
/home/jakob/code/pjdfstest/tests/symlink/03.t .. 
1..6
not ok 1 - tried 'symlink 23ed68f75f1b5eb776df42af2ed2848b3d641179783607d2f1a1deee4edf8f014523df3e81aaaf3e456da127a5067bb0c0450c45c2cff7e7facbe7a832387d4/248b250d4ec8724d5b5d1ededef36f3c2f9c2224897bcd80b328f4d002fd57e6fb6cae83dfcb176c04df37a6b426a778e977102ee49d38f7088a473891d5d1f/bc22aebec731731d0095b92473ab1b0c72c17b64f111ee1c498506f339fe6673378a4015e102b699933f5b91489019cb1cc89d2bb357d41359f1ce0785f843f/c44e68c3caaada10b07d9a2552ac48f7cd67c2ba3b5afc36ef5efc85b6c007f9037559bf3afcbd04b811103be376e78ec53772fd99fc83e15312d4b599d3200/59fc1e2cbc929f4f243e07bc7168a62707a8a185184227b55f3993edc12acc67f7155ad9c6ef4bf119ecec3c8cbc9ba4397011b59a51510cd84820cce7cb73c/f381e07bc3152f9e3120b981c52576948cfd565874f015bb83061ab07bdaf3fe8c0f6564e7f998e0b7a09b45241ee1232b3294999d5c524cd8380725983b72f/1a56838452edf4d37102f7019c060c4e98c4600eff9160461fa7e0d4fbc45ba7d729334bfdec9f8b970aea5dd64435c6c32073a74126ec513a9509646f1c0db/0e1d55ff1e2b709439cf52209f505a10feba0cf1d5d760b4bad10335b3f5bdd436ae98f9811b65c928f13a9f39a81d074ef76ffaeb29f6541d18132786d424b/ef972f65a195add49c08f7bb706ac3ab1230ba719da5a9bc723f50bdaa127f37e7ea5289f6cc5b06eba272bd0919922a0c1cb1ac5ec6915674dd084023b209b/92de4c5fc2d65acd49bdfb3bce0c0adaf5a5f4c14bbc7a79f1921d3f66f0973b08a779876170859b8a75e822e0e99fb310680c32ce2d0ad559ed01d2fbd07fb/ddf2464d41afcd55c63ba9e864e0566587a22aad0da07d6bdd6a2a7a53f41bc62e5ddea1fd5fd9515cb4deb9a4353ae5356f2d5012f6a9038a545ba73c540e1/3f732b80482cfa788fdb60ddada000074210d210f5bcc815ef4d07249d3a253c02237c0734c82945e28ba6d3c1b8ca2371ecccbfd1626c6409f9b63f235ecef/02b98d5a6ef457fa2aab857c667b9e3bc2d4ceb171aa757628ac7b52afd75a475d1590fb5c9213736144dc069758469673fccd519f5c09b07dbf3c8f8230842/ede5fbbd47ff4d152c0cef6aaf28374a4efba8d0d2b80397b9f88d94429d1ddeb04599acbb422cb5a4be4f2a794c70e292abc7c80225b96cfe4794eb4f0ff59/7fdf2daf92bcd3fd64be10782398c9a45c9494c1e41dd0d2f225097f3f56ee0181f438277e2e2e64f9676e705e08ea6625b50df110078499a88c5e4100f2a9a/62fe5fb014fbc604474df5de2b51886a836768e5c4825e2f6276f2b4e80fe052375a31bfc88fe1c4b57cc494485865e6afbaa61b3ffb73d0367c30701dec221/e08f4bd362975dee4f870eddc9e6e94410e4b3a76c042118fb9437407646435bdbd4c86ec08b483dae9cc5319ad5536c04411505e964c59b6f8cde2c8f90d51/bcc1c2f4d3e29a5518cb0e3ed5231a9b2762c1521b25bd0e8fe4dd7ab297eb45ce954c1e7cb1c2c098331334332ac4e62ded1d68b39f2615d663ae960a415af/18848c974aa7a6ee669da70cbbaa8509c036f4a555a80b927b5e2490102bf056026c376ead077e85a8ed3a049fb1b043e7fe54f90f41e45a53262ca4f8e9235/83c012877dda294d7792ab2f4a9ae34df5b50b96528a0356f8fcae346da053c9958be756b4c0dd430dc667215253375dbd83591e408cff510943de7d04cbf1e/9ac097c625dd96155b680b9f5794bd45af747e8ae22b045ee1735ee04ee93b90cbd283b1f119ec777023682a003bded1d4521f561ec1f71c8f5033afb875d8c/89ba1562b64d626ce474369dc4999e68a6e6c3bd286de55a2a3a275b0dd6ce195eb33422fa323ddcbef6ae4954d4fae4b5cb4f2314a56ef0d2ab04154df941e/6b04ec713129cf1e2170c58f7e7d7deafa95f00770d43e3e468b1971be40d6ec525300db2ad5df8f4571483f9e4d98e073c1e444556939a57de6934e1c05a59/50d0980c223384cc720a2159bc811ba196ae1a0e659fbbd18471c56d1c4068c8a13c5629f95c2aa46d6cf87fdd8731529b1f5b19a2da76de5a300bb800b5510/9935ad60b4a1c6968938436e87f9467baeb879262ae556f7e4390cd5f8baf7f2c1315c43906033753e413e32322c2607b4bc8849e00bc06f776b878762b2f77/7829f7dcbd16a1b9ac8a6d9b9501a5903cd69bdd9f1b2c16336961ad9256b5a2c13014d4efd8e749f8dfcbe97f3545964eede49d8e7a6367ae836ca938c2e3d/603b1ebbddd410b01ac030a4b7d8fa1ea9ff8a98ef3690514a762aae2e0a199e9b18df8d9dae416c34df6d3cd08243a1a85e58ede14efd279d1a5fcce320945/dfe6ad9a58012d7a0209adb3cd5e4bb5fecb7a7437afd1fc8dda6b86a340ca50ebe8aaa7e408bdb4bc9f80e10673155a3f668fe5cc87888f037fc71be81ba05/6b2bd09ecfb50e52e6fcbc23e71becdb6cb3c07ac4fcd89553eaac16cc998e8bacc2d906299e990626100a6f7750c4d9c23d19e4b72db720a0f18a66a4db871/a9354c54f3cc39df1aaf9e46e385d8b755d5349489a6d6afc3a2d63dfa2e44227df6af8fb6b0bc6487e010630fc07b820ec033d4e44b6152ae8b6801baf918b/e4400c8deecd70b6d0b181e1f1ef1ba563361a86c236601b09212c41c25e1e9c843ae1c52fde9c61dc8f26092ea103d222f68be09daa0ca6b70763a916b3a70/c862a9e0203028b1c88453f3b4aef1b93d5272b15d786fb8acd311669492f345051208b9e0ec1e7340d7154c9ea072f63323a05731cff15092c7e47985d2cf4 pjdfstest_b377cf7fa7a840a8e67c1329e3a9dca7',
 expected 0, got ENAMETOOLONG
not ok 2 - tried 'unlink pjdfstest_b377cf7fa7a840a8e67c1329e3a9dca7', expected 0, got ENOENT
ok 3
ok 4
ok 5
ok 6
Failed 2/6 subtests 

Test Summary Report
-------------------
/home/jakob/code/pjdfstest/tests/symlink/03.t (Wstat: 0 Tests: 6 Failed: 2)
  Failed tests:  1-2
Files=1, Tests=6,  1 wallclock secs ( 0.03 usr  0.01 sys +  0.69 cusr  0.78 csys =  1.51 CPU)
Result: FAIL
```

```
root@brikett:/var/tmp/g/b# prove -v /home/jakob/code/pjdfstest/tests/utimensat/05.t
/home/jakob/code/pjdfstest/tests/utimensat/05.t .. 
1..16
ok 1
ok 2
ok 3
ok 4
ok 5
ok 6
not ok 7 - tried 'lstat pjdfstest_f1cd2b8794f82da55def3ffa9af7556f atime', expected 1960000000, got 1784144798
ok 8
ok 9
ok 10
ok 11
ok 12
ok 13
ok 14
ok 15
ok 16
Failed 1/16 subtests 

Test Summary Report
-------------------
/home/jakob/code/pjdfstest/tests/utimensat/05.t (Wstat: 0 Tests: 16 Failed: 1)
  Failed test:  7
Files=1, Tests=16,  0 wallclock secs ( 0.03 usr  0.00 sys +  0.04 cusr  0.07 csys =  0.14 CPU)
Result: FAIL
```
