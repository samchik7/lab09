  /Users/sam/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_download.cmake:26 (include)
  /Users/sam/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/projects/GTest/hunter.cmake:8 (include)
  /Users/sam/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:62 (include)
  CMakeLists.txt:24 (hunter_add_package)


CMake Deprecation Warning at /Users/sam/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_lock_directory.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.10 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value.  Or, use the <min>...<max> syntax
  to tell CMake that the project requires at least <min> but has been updated
  to work with policies introduced by <max> or earlier.
Call Stack (most recent call first):
  /Users/sam/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_make_directory.cmake:7 (include)
  /Users/sam/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_save_to_cache.cmake:8 (include)
  /Users/sam/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_download.cmake:26 (include)
  /Users/sam/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/projects/GTest/hunter.cmake:8 (include)
  /Users/sam/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:62 (include)
  CMakeLists.txt:24 (hunter_add_package)


-- [hunter] GTEST_ROOT: /Users/sam/.hunter/_Base/23f1b5a/38776ca/302e72f/Install (ver.: 1.11.0)
-- Configuring done (2.3s)
-- Generating done (0.0s)
-- Build files have been written to: /Users/sam/samchik7/workspace/projects/lab09/_build
sam@Noutbuk-Samvel lab09 % cmake --build _build --target package
make: *** No rule to make target `package'.  Stop.
sam@Noutbuk-Samvel lab09 % travis login --auto 
zsh: command not found: travis
sam@Noutbuk-Samvel lab09 % travis enable
zsh: command not found: travis
sam@Noutbuk-Samvel lab09 % clear

sam@Noutbuk-Samvel lab09 % cd ..
sam@Noutbuk-Samvel projects % ls
lab02	lab03	lab04	lab05	lab06	lab07	lab09
sam@Noutbuk-Samvel projects % ды 
zsh: command not found: ды
sam@Noutbuk-Samvel projects % ls
lab02	lab03	lab04	lab05	lab06	lab07
sam@Noutbuk-Samvel projects % https://github.com/Syrex333/lab0 
sam@Noutbuk-Samvel projects % git clone https://github.com/Syrex333/lab09 /lab08
fatal: could not create work tree dir '/lab08': Read-only file system
sam@Noutbuk-Samvel projects %  git clone https://github.com/Syrex333/lab09 lab08
Cloning into 'lab08'...
remote: Enumerating objects: 264, done.
remote: Counting objects: 100% (264/264), done.
remote: Compressing objects: 100% (126/126), done.
remote: Total 264 (delta 105), reused 260 (delta 104), pack-reused 0 (from 0)
Receiving objects: 100% (264/264), 979.22 KiB | 3.50 MiB/s, done.
Resolving deltas: 100% (105/105), done.
sam@Noutbuk-Samvel projects % git clone  git clone https://github.com/Syrex333/lab09 lab08 
fatal: Too many arguments.

usage: git clone [<options>] [--] <repo> [<dir>]

    -v, --verbose         be more verbose
    -q, --quiet           be more quiet
    --progress            force progress reporting
    --reject-shallow      don't clone shallow repository
    -n, --no-checkout     don't create a checkout
    --bare                create a bare repository
    --mirror              create a mirror repository (implies bare)
    -l, --local           to clone from a local repository
    --no-hardlinks        don't use local hardlinks, always copy
    -s, --shared          setup as shared repository
    --recurse-submodules[=<pathspec>]
                          initialize submodules in the clone
    --recursive ...       alias of --recurse-submodules
    -j, --jobs <n>        number of submodules cloned in parallel
    --template <template-directory>
                          directory from which templates will be used
    --reference <repo>    reference repository
    --reference-if-able <repo>
                          reference repository
    --dissociate          use --reference only while cloning
    -o, --origin <name>   use <name> instead of 'origin' to track upstream
    -b, --branch <branch>
                          checkout <branch> instead of the remote's HEAD
    -u, --upload-pack <path>
                          path to git-upload-pack on the remote
    --depth <depth>       create a shallow clone of that depth
    --shallow-since <time>
                          create a shallow clone since a specific time
    --shallow-exclude <revision>
                          deepen history of shallow clone, excluding rev
    --single-branch       clone only one branch, HEAD or --branch
    --no-tags             don't clone any tags, and make later fetches not to follow them
    --shallow-submodules  any cloned submodules will be shallow
    --separate-git-dir <gitdir>
                          separate git dir from working tree
    -c, --config <key=value>
                          set config inside the new repository
    --server-option <server-specific>
                          option to transmit
    -4, --ipv4            use IPv4 addresses only
    -6, --ipv6            use IPv6 addresses only
    --filter <args>       object filtering
    --also-filter-submodules
                          apply partial clone filters to submodules
    --remote-submodules   any cloned submodules will use their remote-tracking branch
    --sparse              initialize sparse-checkout file to include only files at root
    --bundle-uri <uri>    a URI for downloading bundles before fetching from origin remote

sam@Noutbuk-Samvel projects %  git clone https://github.com/Syrex333/lab09 lab08
fatal: destination path 'lab08' already exists and is not an empty directory.
sam@Noutbuk-Samvel projects % git clone https://github.com/Syrex333/lab0'''''''''''''''''''''''''''''''''''''''''...........9
sam@Noutbuk-Samvel projects % 000000099999999999999999999999999999999999999999999github-release --version
zsh: command not found: 000000099999999999999999999999999999999999999999999github-release
sam@Noutbuk-Samvel projects % github-release info -u ${GITHUB_USERNAME} -r lab09
zsh: command not found: github-release
sam@Noutbuk-Samvel projects % 
sam@Noutbuk-Samvel projects % github-release release \
>  --user ${GITHUB_USERNAME} \
    --repo lab09 \
    --tag v0.1.0.0 \
    --name "libprint" \
    --description "my first release"
zsh: command not found: github-release
sam@Noutbuk-Samvel projects % export PACKAGE_OS=`uname -s` PACKAGE_ARCH=`uname -m`
sam@Noutbuk-Samvel projects % export PACKAGE_FILENAME=print-${PACKAGE_OS}-${PACKAGE_ARCH}.tar.gz
sam@Noutbuk-Samvel projects % github-release upload \
    --user ${GITHUB_USERNAME} \
    --repo lab09 \
    --tag v0.1.0.0 \
    --name "${PACKAGE_FILENAME}" \
    --file _build/*.tar.gz
zsh: no matches found: _build/*.tar.gz
sam@Noutbuk-Samvel projects % github-release info -u ${GITHUB_USERNAME} -r lab09
zsh: command not found: github-release
sam@Noutbuk-Samvel projects % м
zsh: command not found: м
sam@Noutbuk-Samvel projects % wget https://github.com/${GITHUB_USERNAME}/lab09/releases/download/v0.1.0.0/${PACKAGE_FILENAME}
--2025-05-15 19:26:23--  https://github.com/samchik7/lab09/releases/download/v0.1.0.0/print-Darwin-x86_64.tar.gz
Распознаётся github.com (github.com)… 140.82.121.4
Подключение к github.com (github.com)|140.82.121.4|:443... соединение установлено.
HTTP-запрос отправлен. Ожидание ответа… 404 Not Found
2025-05-15 19:26:24 ОШИБКА 404: Not Found.

sam@Noutbuk-Samvel projects % tar -ztf ${PACKAGE_FILENAME}
tar: Error opening archive: Failed to open 'print-Darwin-x86_64.tar.gz'
sam@Noutbuk-Samvel projects % tar -ztf ${PACKAGE_FILENAME}
