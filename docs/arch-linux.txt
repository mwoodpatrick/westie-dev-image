 1140  git switch --orphan arch-linux 
 1141  ld
 1142  ls
 1143  git checkout --merge main README.md
 1144  ls
 1145  git log README.md
 1146  nvim README.md 
 1147  git checkout --merge main .vscode
 1148  ls
 1149  ls .vscode/
 1150  git checkout --merge main .devcontainer
 1151  ls -al
 1152  git checkout --merge main docs
 1153  git checkout --merge main .gitignore
 1154  git checkout --merge main LICENSE
 1155  git checkout --merge main NOTICE.txt
 1156  git checkout --merge main package.json
 1157  git checkout --merge main src/javascript-node
 1158  git checkout --merge main src/base-ubuntu src/base-arch
 1159  git checkout --merge main src/base-ubuntu 
 1160  mv main src/base-ubuntu src/base-arch
 1161  cd src/base-arch
 1162  ls src
 1163  ls main
 1164  mv src/base-ubuntu src/base-arch
 1165  cd src/base-arch/
 1166  ls
 1167  ls -al
 1168  cd .devcontainer/
 1169  ls
 1170  ls -al
 1171  cd ..
 1172  ls -al
 1173  cd ../..
 1174  ls -al
 1175  nvim .git/config 
 1176  cd src/
 1177  ls
 1178  cd base-arch/
 1179  ls
 1180  ls -al
 1181  nvim .devcontainer/Dockerfile 
 1182  git status
 1183  ls
 1184  cd ..
 1185  git restore base-ubuntu
 1186  git status
 1187  git rm --cached base_ubuntu
 1188  git rm --cached base_ubuntu/...
 1189  git rm --cached  base-ubuntu/...
 1190  c
 1191  git status
 1192  git revert base-ubuntu/...
 1193  git rm --cached base-ubuntu/README.md
 1194  git rm --cached base-ubuntu/history/...
 1195  git status > junk
 1196  gvim junk 
 1197  nvim junk 
 1198  source junk 
 1199  git status
 1200  ht
 1201  git checkout --merge main src/base-ubuntu
 1202  git checkout --merge main src/base-ubuntu/...
 1203  git checkout main --merge main src/base-ubuntu/...
 1204  git checkout --merge main src/base-ubuntu
 1205  git checkout --merge main base-ubuntu
 1206  ls
 1207  git status
 1208  ls
 1209  ls base-arch/
 1210  mv base-arch base-arch.old
 1211  ls
 1212  cp -pr base-ubuntu base-arch
 1213  git status
 1214  git add base-arch
 1215  git status
 1216  git rm --cached base_arch/...
 1217  git rm --cached base_arch/*
 1218  source junk
 1219  git status
 1220  gvim junk 
 1221  nvim junk 
 1222  source junk 
 1223  git status
 1224  ls base-arch
 1225  cp base-arch.old/.devcontainer/Dockerfile base-arch/.devcontainer/Dockerfile
 1226  nvim base-arch/.devcontainer/Dockerfile
 1227  diff base-arch.old/README.md base-arch/README.md 
 1228  rm -rf base-arch.old
 1229  git status
 1230  git restore base-ubuntu/...
 1231  rm -rf base-ubuntu/
 1232  git status
 1233  rm base-arch/history/ junk 
 1234  git status
 1235  git commit -m "start on arch-linux"
 1236  git push
 1237  git push --set-upstream origin arch-linux
 1238  cd ..
 1239  ls
 1240  h
 1241  h > docs/arch-linux.md
