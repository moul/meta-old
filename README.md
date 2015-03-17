# meta
POC: meta repository with submodules for each available repositories

# commands

    make add_submodules  # git submodule adds repositories retrieved using
                         # GitHub API

    git clone --recursive https://github.com/moul/meta  # git clone meta and
                                                        # all sub repositories

    git submodule init && \                             # initialize submodules
    git submodule update                                # git pull submodules
