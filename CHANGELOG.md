# Changelog

## [**Next release**](https://github.com/netdata/netdata/tree/HEAD)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.33.1...HEAD)

**Merged pull requests:**

- reduce min `dbengine anomaly rate every` 60s-\>30s [\#12543](https://github.com/netdata/netdata/pull/12543) ([andrewm4894](https://github.com/andrewm4894))
- Allocate buffer and release on callback when executing agent CLI commands [\#12540](https://github.com/netdata/netdata/pull/12540) ([stelfrag](https://github.com/stelfrag))
- feat\(collectors\): update go.d.plugin version to v0.32.0 [\#12536](https://github.com/netdata/netdata/pull/12536) ([ilyam8](https://github.com/ilyam8))
- fix: use internal defaults for sched policy/oom score in native packages [\#12529](https://github.com/netdata/netdata/pull/12529) ([ilyam8](https://github.com/ilyam8))
- docs: fix unresolved file references [\#12528](https://github.com/netdata/netdata/pull/12528) ([ilyam8](https://github.com/ilyam8))
- fix\(kickstart.sh\): use `$ROOTCMD` when setting auto updates [\#12526](https://github.com/netdata/netdata/pull/12526) ([ilyam8](https://github.com/ilyam8))
- fix\(netdata-updater\): properly handle update for debian packages [\#12524](https://github.com/netdata/netdata/pull/12524) ([ilyam8](https://github.com/ilyam8))
- fix: Netdata segfault because of 2 timex.plugin threads [\#12512](https://github.com/netdata/netdata/pull/12512) ([ilyam8](https://github.com/ilyam8))
- fix centos7 gpg key issue [\#12506](https://github.com/netdata/netdata/pull/12506) ([maneamarius](https://github.com/maneamarius))
- Use live charts to count the total number of dimensions. [\#12504](https://github.com/netdata/netdata/pull/12504) ([vkalintiris](https://github.com/vkalintiris))
- feat\(collectors/timex.plugin\): add clock status chart [\#12501](https://github.com/netdata/netdata/pull/12501) ([ilyam8](https://github.com/ilyam8))
- PR template: Include user information section [\#12499](https://github.com/netdata/netdata/pull/12499) ([kickoke](https://github.com/kickoke))
- Adjust timex.plugin information to be less cryptic [\#12495](https://github.com/netdata/netdata/pull/12495) ([DanTheMediocre](https://github.com/DanTheMediocre))
- fix: open fd 3 before first use in the netdata-updater.sh script [\#12491](https://github.com/netdata/netdata/pull/12491) ([ilyam8](https://github.com/ilyam8))
- timex: this plugin enables timex plugin for non-linux systems [\#12489](https://github.com/netdata/netdata/pull/12489) ([surajnpn](https://github.com/surajnpn))
- Bump the debhelper compat level to 10 in our DEB packaging code. [\#12488](https://github.com/netdata/netdata/pull/12488) ([Ferroin](https://github.com/Ferroin))
- minor - fix configure output of eBPF [\#12471](https://github.com/netdata/netdata/pull/12471) ([underhood](https://github.com/underhood))
- Don't send an alert snapshot with snapshot\_id 0 [\#12469](https://github.com/netdata/netdata/pull/12469) ([MrZammler](https://github.com/MrZammler))
- Update ebpf dashboard [\#12467](https://github.com/netdata/netdata/pull/12467) ([thiagoftsm](https://github.com/thiagoftsm))
- docs\(collectors/python.d\): remove mention of compatibility with py2/py3 [\#12465](https://github.com/netdata/netdata/pull/12465) ([ilyam8](https://github.com/ilyam8))
- feat\(collectors/cgroups\): prefer `blkio.*_recursive` when available [\#12462](https://github.com/netdata/netdata/pull/12462) ([ilyam8](https://github.com/ilyam8))
- Updated static build components to latest versions. [\#12461](https://github.com/netdata/netdata/pull/12461) ([ktsaou](https://github.com/ktsaou))
- Implement fine-grained errors to cloud queries [\#12460](https://github.com/netdata/netdata/pull/12460) ([underhood](https://github.com/underhood))
- Extend aclk-state [\#12458](https://github.com/netdata/netdata/pull/12458) ([underhood](https://github.com/underhood))
- Update dashboard to version v2.21.8. [\#12455](https://github.com/netdata/netdata/pull/12455) ([netdatabot](https://github.com/netdatabot))
- fix\(collectors/cgroups\): use different context for cgroup network charts [\#12454](https://github.com/netdata/netdata/pull/12454) ([ilyam8](https://github.com/ilyam8))
- Add delay on missing priv\_key [\#12450](https://github.com/netdata/netdata/pull/12450) ([underhood](https://github.com/underhood))
- fix unclaimed agents [\#12449](https://github.com/netdata/netdata/pull/12449) ([underhood](https://github.com/underhood))
- apps.plugin: fix for plugin sending unnecessary data in freebsd [\#12446](https://github.com/netdata/netdata/pull/12446) ([surajnpn](https://github.com/surajnpn))
- fix\(cups.plugin\): add `cups` prefix to chart context [\#12444](https://github.com/netdata/netdata/pull/12444) ([ilyam8](https://github.com/ilyam8))
- Skip `foreach` alarms for dimensions of anomaly rate chart. [\#12441](https://github.com/netdata/netdata/pull/12441) ([vkalintiris](https://github.com/vkalintiris))
- fix: CPU frequency detection of FreeBSD [\#12440](https://github.com/netdata/netdata/pull/12440) ([ilyam8](https://github.com/ilyam8))
- fix install type in netdata-uninstaller.sh [\#12438](https://github.com/netdata/netdata/pull/12438) ([maneamarius](https://github.com/maneamarius))
- fix\(kickstart.sh\): prefer shasum over sha256sum [\#12429](https://github.com/netdata/netdata/pull/12429) ([ilyam8](https://github.com/ilyam8))
- Docs: Fix broken link [\#12428](https://github.com/netdata/netdata/pull/12428) ([kickoke](https://github.com/kickoke))
- Fix OS name for older agent versions streaming to a parent [\#12425](https://github.com/netdata/netdata/pull/12425) ([stelfrag](https://github.com/stelfrag))
- fix: ensure claim\_id is always sent lowercase as string [\#12423](https://github.com/netdata/netdata/pull/12423) ([underhood](https://github.com/underhood))
- fix: lowercase uuidgen [\#12422](https://github.com/netdata/netdata/pull/12422) ([ilyam8](https://github.com/ilyam8))
- fix: add a delay between starting Netdata and checking pids [\#12420](https://github.com/netdata/netdata/pull/12420) ([ilyam8](https://github.com/ilyam8))
- fix\(charts.d.plugin\): fix recursion in apcupsd\_check and enable it again [\#12418](https://github.com/netdata/netdata/pull/12418) ([ilyam8](https://github.com/ilyam8))
- Add content for eBPF documentation [\#12417](https://github.com/netdata/netdata/pull/12417) ([thiagoftsm](https://github.com/thiagoftsm))
- fix: temporarily disable charts.d apcupsd collectors [\#12415](https://github.com/netdata/netdata/pull/12415) ([ilyam8](https://github.com/ilyam8))
- Add additional link to badges doc [\#12412](https://github.com/netdata/netdata/pull/12412) ([Steve8291](https://github.com/Steve8291))
- chore: remove contrib/sles11 [\#12410](https://github.com/netdata/netdata/pull/12410) ([ilyam8](https://github.com/ilyam8))
- Update dashboard to version v2.21.3. [\#12407](https://github.com/netdata/netdata/pull/12407) ([netdatabot](https://github.com/netdatabot))
- chore: remove "web files" options leftovers [\#12403](https://github.com/netdata/netdata/pull/12403) ([ilyam8](https://github.com/ilyam8))
- Allow updates without environment files in some cases. [\#12400](https://github.com/netdata/netdata/pull/12400) ([Ferroin](https://github.com/Ferroin))
- Reorder functions properly in updater script. [\#12399](https://github.com/netdata/netdata/pull/12399) ([Ferroin](https://github.com/Ferroin))
- Fix crash when netdatacli command output too long [\#12393](https://github.com/netdata/netdata/pull/12393) ([underhood](https://github.com/underhood))
- Dont check host health enabled if host is null [\#12392](https://github.com/netdata/netdata/pull/12392) ([MrZammler](https://github.com/MrZammler))
- Update build/m4/ax\_pthread.m4 [\#12390](https://github.com/netdata/netdata/pull/12390) ([vkalintiris](https://github.com/vkalintiris))
- Delay removed event for 60 seconds after the chart's last collected time [\#12388](https://github.com/netdata/netdata/pull/12388) ([MrZammler](https://github.com/MrZammler))
- Remove unecessary error report for proc and sys files [\#12385](https://github.com/netdata/netdata/pull/12385) ([thiagoftsm](https://github.com/thiagoftsm))
- feat\(statsd.plugin\): add Asterisk configuration file with synthetic charts [\#12381](https://github.com/netdata/netdata/pull/12381) ([ilyam8](https://github.com/ilyam8))
- fix: handle double host prefix when Netdata running in a podman container [\#12380](https://github.com/netdata/netdata/pull/12380) ([ilyam8](https://github.com/ilyam8))
- fix\(ebpf.plugin\): remove pid file on exit [\#12379](https://github.com/netdata/netdata/pull/12379) ([thiagoftsm](https://github.com/thiagoftsm))
- fix: shellcheck warnings in docker run.sh [\#12377](https://github.com/netdata/netdata/pull/12377) ([ilyam8](https://github.com/ilyam8))
- Fix version handling issues in release workflow. [\#12375](https://github.com/netdata/netdata/pull/12375) ([Ferroin](https://github.com/Ferroin))
- Update Agent version in the Swagger API [\#12374](https://github.com/netdata/netdata/pull/12374) ([tkatsoulas](https://github.com/tkatsoulas))
- Fix handling of checks for newer updater script on update. [\#12367](https://github.com/netdata/netdata/pull/12367) ([Ferroin](https://github.com/Ferroin))
- Fix handling of pushing commits for release process. [\#12359](https://github.com/netdata/netdata/pull/12359) ([Ferroin](https://github.com/Ferroin))
- Fix chart synchronization with the cloud [\#12356](https://github.com/netdata/netdata/pull/12356) ([stelfrag](https://github.com/stelfrag))
- minor - fix analytics\_build\_info [\#12354](https://github.com/netdata/netdata/pull/12354) ([underhood](https://github.com/underhood))
- Docs fix: Add missing frontmatter [\#12353](https://github.com/netdata/netdata/pull/12353) ([kickoke](https://github.com/kickoke))
- fix\(health\): make ioping\_disk\_latency alarm less sensitive [\#12351](https://github.com/netdata/netdata/pull/12351) ([ilyam8](https://github.com/ilyam8))
- Improve agent to cloud synchronization performance [\#12348](https://github.com/netdata/netdata/pull/12348) ([stelfrag](https://github.com/stelfrag))
- Prepend context in anomaly rate dimension id. [\#12342](https://github.com/netdata/netdata/pull/12342) ([vkalintiris](https://github.com/vkalintiris))
- Redirect dependency handling script output to logfile when running from the updater. [\#12341](https://github.com/netdata/netdata/pull/12341) ([Ferroin](https://github.com/Ferroin))
- Remove owner check from webserver [\#12339](https://github.com/netdata/netdata/pull/12339) ([thiagoftsm](https://github.com/thiagoftsm))
- fix: container virtualization detection with systemd-detect-virt [\#12338](https://github.com/netdata/netdata/pull/12338) ([ilyam8](https://github.com/ilyam8))
- fix: use default "bind to" in native packages [\#12336](https://github.com/netdata/netdata/pull/12336) ([ilyam8](https://github.com/ilyam8))
- Use the built agent version for Netdata static build archive name. [\#12335](https://github.com/netdata/netdata/pull/12335) ([Ferroin](https://github.com/Ferroin))
- Add latency dimension [\#12329](https://github.com/netdata/netdata/pull/12329) ([Steve8291](https://github.com/Steve8291))
- Remove check for config file in stock conf dir [\#12327](https://github.com/netdata/netdata/pull/12327) ([Steve8291](https://github.com/Steve8291))
- fix underscore in libnetfilter-acct-dev package [\#12326](https://github.com/netdata/netdata/pull/12326) ([Steve8291](https://github.com/Steve8291))
- fix: returning 0 for CPU frequency when unknown [\#12323](https://github.com/netdata/netdata/pull/12323) ([ilyam8](https://github.com/ilyam8))
- Add a dry run mode to the kickstart script. [\#12322](https://github.com/netdata/netdata/pull/12322) ([Ferroin](https://github.com/Ferroin))
- fix\(health\): adjust 10s\_ipv4\_tcp\_resets\_sent warn trigger [\#12320](https://github.com/netdata/netdata/pull/12320) ([ilyam8](https://github.com/ilyam8))
- CO-RE and syscalls [\#12318](https://github.com/netdata/netdata/pull/12318) ([thiagoftsm](https://github.com/thiagoftsm))
- Fix 'connect' typo anomaly-detection-python.md [\#12317](https://github.com/netdata/netdata/pull/12317) ([DanTheMediocre](https://github.com/DanTheMediocre))
- Add ml notebooks [\#12313](https://github.com/netdata/netdata/pull/12313) ([andrewm4894](https://github.com/andrewm4894))
- Provide better handling of config files in Docker containers. [\#12310](https://github.com/netdata/netdata/pull/12310) ([Ferroin](https://github.com/Ferroin))
- Replace write with read locks [\#12309](https://github.com/netdata/netdata/pull/12309) ([MrZammler](https://github.com/MrZammler))
- adds node\_id into mirrored\_hosts list [\#12307](https://github.com/netdata/netdata/pull/12307) ([underhood](https://github.com/underhood))
- fix: CPU frequency detection for some containers [\#12306](https://github.com/netdata/netdata/pull/12306) ([ilyam8](https://github.com/ilyam8))
- introduce new chart for process states metrics [\#12305](https://github.com/netdata/netdata/pull/12305) ([surajnpn](https://github.com/surajnpn))
- fix uninstall using kickstart flag [\#12304](https://github.com/netdata/netdata/pull/12304) ([maneamarius](https://github.com/maneamarius))
- Workflow to trigger cloud regression e2e tests [\#12299](https://github.com/netdata/netdata/pull/12299) ([dimko](https://github.com/dimko))
- Fixing stderr output when testing tmpdir [\#12298](https://github.com/netdata/netdata/pull/12298) ([godismyjudge95](https://github.com/godismyjudge95))
- chore: remove unused variable in the system-info script [\#12297](https://github.com/netdata/netdata/pull/12297) ([ilyam8](https://github.com/ilyam8))
- Switch to using netdata-updater.sh to toggle auto updates on and off when installing. [\#12296](https://github.com/netdata/netdata/pull/12296) ([Ferroin](https://github.com/Ferroin))
- Pull in build dependencies when updating a locally built install. [\#12294](https://github.com/netdata/netdata/pull/12294) ([Ferroin](https://github.com/Ferroin))
- fix: cpu system info detection on macOS [\#12293](https://github.com/netdata/netdata/pull/12293) ([ilyam8](https://github.com/ilyam8))
- Only store alert hashes when iterated from localhost [\#12292](https://github.com/netdata/netdata/pull/12292) ([MrZammler](https://github.com/MrZammler))
- fix\(kickstart\): use correct syntax for claiming extra parameters [\#12289](https://github.com/netdata/netdata/pull/12289) ([ilyam8](https://github.com/ilyam8))
- feat\(health\): add charts.d/nut alarms [\#12285](https://github.com/netdata/netdata/pull/12285) ([ilyam8](https://github.com/ilyam8))
- Adjust cloud dimension update frequency  [\#12284](https://github.com/netdata/netdata/pull/12284) ([stelfrag](https://github.com/stelfrag))
- Fix incorrect install type on some older nightly installs. [\#12282](https://github.com/netdata/netdata/pull/12282) ([Ferroin](https://github.com/Ferroin))
- Timex: make offset rrd independently configurable [\#12281](https://github.com/netdata/netdata/pull/12281) ([d--j](https://github.com/d--j))
- add host labels \_aclk\_ng\_new\_cloud\_protocol [\#12278](https://github.com/netdata/netdata/pull/12278) ([underhood](https://github.com/underhood))
- Use the new error mechanism in case host not found [\#12277](https://github.com/netdata/netdata/pull/12277) ([underhood](https://github.com/underhood))
- Add proper handling for legacy kickstart install detection. [\#12273](https://github.com/netdata/netdata/pull/12273) ([Ferroin](https://github.com/Ferroin))
- Fixed typos in docs/Running-behind-haproxy.md [\#12272](https://github.com/netdata/netdata/pull/12272) ([RatishT](https://github.com/RatishT))
- Change default OOM score and scheduling policy to behave more sanely. [\#12271](https://github.com/netdata/netdata/pull/12271) ([Ferroin](https://github.com/Ferroin))
- Add Ubuntu 22.04 to CI and package builds. [\#12269](https://github.com/netdata/netdata/pull/12269) ([Ferroin](https://github.com/Ferroin))
- Add Fedora 36 to CI and package builds. [\#12268](https://github.com/netdata/netdata/pull/12268) ([Ferroin](https://github.com/Ferroin))
- Null terminate decoded\_query\_string if there are no url parameters. [\#12266](https://github.com/netdata/netdata/pull/12266) ([MrZammler](https://github.com/MrZammler))
- delete package.json [\#12265](https://github.com/netdata/netdata/pull/12265) ([ilyam8](https://github.com/ilyam8))
- Docs: Fix typo in step-10.md [\#12263](https://github.com/netdata/netdata/pull/12263) ([tnagorran](https://github.com/tnagorran))
- Set a version number for the metadata database to better handle future data migrations [\#12249](https://github.com/netdata/netdata/pull/12249) ([stelfrag](https://github.com/stelfrag))
- Revise claiming error message in kickstart script. [\#12248](https://github.com/netdata/netdata/pull/12248) ([Ferroin](https://github.com/Ferroin))
- Add a check to make sure internal chart state is initialized [\#12244](https://github.com/netdata/netdata/pull/12244) ([stelfrag](https://github.com/stelfrag))
- eBPF installation fixes [\#12242](https://github.com/netdata/netdata/pull/12242) ([thiagoftsm](https://github.com/thiagoftsm))
- Add a fix to correctly register child nodes to the cloud via a parent [\#12241](https://github.com/netdata/netdata/pull/12241) ([stelfrag](https://github.com/stelfrag))
- Fix builds where HAVE\_C\_\_\_ATOMIC is not defined. [\#12240](https://github.com/netdata/netdata/pull/12240) ([vkalintiris](https://github.com/vkalintiris))
- Adds more info to aclk-state API call [\#12231](https://github.com/netdata/netdata/pull/12231) ([underhood](https://github.com/underhood))
- minor - remove dead code [\#12230](https://github.com/netdata/netdata/pull/12230) ([underhood](https://github.com/underhood))
- Fix node information send to the cloud for older agent versions [\#12223](https://github.com/netdata/netdata/pull/12223) ([stelfrag](https://github.com/stelfrag))
- Fixed typo in docs/guides/monitor/anomaly-detection-python.md file [\#12220](https://github.com/netdata/netdata/pull/12220) ([MariosMarinos](https://github.com/MariosMarinos))
- \[makeself\] Fix license URL [\#12219](https://github.com/netdata/netdata/pull/12219) ([Daniel15](https://github.com/Daniel15))
- Update github's code owners configuration. [\#12213](https://github.com/netdata/netdata/pull/12213) ([vkalintiris](https://github.com/vkalintiris))
- Skip training of constant metrics. [\#12212](https://github.com/netdata/netdata/pull/12212) ([vkalintiris](https://github.com/vkalintiris))
- Add -W keepopenfds option. [\#12211](https://github.com/netdata/netdata/pull/12211) ([vkalintiris](https://github.com/vkalintiris))
- Skip info field in protobuf alerts messages if it doesn't exist. [\#12210](https://github.com/netdata/netdata/pull/12210) ([MrZammler](https://github.com/MrZammler))
- Remove chart specific configuration from netdata.conf except enabled [\#12209](https://github.com/netdata/netdata/pull/12209) ([stelfrag](https://github.com/stelfrag))
- Fix two small typos in documentation [\#12208](https://github.com/netdata/netdata/pull/12208) ([xrgman](https://github.com/xrgman))
- Fix `hpssa` parse error [\#12206](https://github.com/netdata/netdata/pull/12206) ([wooyey](https://github.com/wooyey))
- Add support to the updater to toggle auto-updates on and off. [\#12202](https://github.com/netdata/netdata/pull/12202) ([Ferroin](https://github.com/Ferroin))
- Improve cleaning up of orphan hosts [\#12201](https://github.com/netdata/netdata/pull/12201) ([stelfrag](https://github.com/stelfrag))
- Fix detection of existing installs. [\#12199](https://github.com/netdata/netdata/pull/12199) ([Ferroin](https://github.com/Ferroin))
- Store dimension hidden option in the metadata db [\#12196](https://github.com/netdata/netdata/pull/12196) ([stelfrag](https://github.com/stelfrag))
- make netdata-uninstaller.sh POSIX compatibility and add --uninstall flag… [\#12195](https://github.com/netdata/netdata/pull/12195) ([maneamarius](https://github.com/maneamarius))
- docs: document the issue with seccomp and claiming [\#12192](https://github.com/netdata/netdata/pull/12192) ([ilyam8](https://github.com/ilyam8))
- fix\(docs\): unresolved file references [\#12191](https://github.com/netdata/netdata/pull/12191) ([ilyam8](https://github.com/ilyam8))
- Update libs code [\#12190](https://github.com/netdata/netdata/pull/12190) ([thiagoftsm](https://github.com/thiagoftsm))
- fix\(python.d/nvidia\_smi\): use uid when can't find the username [\#12184](https://github.com/netdata/netdata/pull/12184) ([ilyam8](https://github.com/ilyam8))
- Fix typos [\#12183](https://github.com/netdata/netdata/pull/12183) ([rex4539](https://github.com/rex4539))
- Revert "Overhaul handling of auto-updates in the installer code. \(\#12076 [\#12182](https://github.com/netdata/netdata/pull/12182) ([Ferroin](https://github.com/Ferroin))
- Add warning about broken Docker hosts in container entrypoint. [\#12175](https://github.com/netdata/netdata/pull/12175) ([Ferroin](https://github.com/Ferroin))
- tidy up the installer script usage message [\#12171](https://github.com/netdata/netdata/pull/12171) ([petecooper](https://github.com/petecooper))
- Remove check for ACLK\_NG and PROMETHEUS\_WRITE in order to assume PROTOBUF [\#12168](https://github.com/netdata/netdata/pull/12168) ([MrZammler](https://github.com/MrZammler))
- Bundle protobuf on CentOS 7 and earlier. [\#12167](https://github.com/netdata/netdata/pull/12167) ([Ferroin](https://github.com/Ferroin))
- add `stress-ng` and `gremlin` to apps\_groups.conf [\#12165](https://github.com/netdata/netdata/pull/12165) ([andrewm4894](https://github.com/andrewm4894))
- Fix alerts to raise correctly when the delay and repeat parameters are used together. [\#12164](https://github.com/netdata/netdata/pull/12164) ([erdem2000](https://github.com/erdem2000))
- fix: claiming with wget [\#12163](https://github.com/netdata/netdata/pull/12163) ([ilyam8](https://github.com/ilyam8))
- fix: CPU frequency calculation in system-info.sh [\#12162](https://github.com/netdata/netdata/pull/12162) ([ilyam8](https://github.com/ilyam8))
- Docs fix: Claim nodes in the kickstart script [\#12161](https://github.com/netdata/netdata/pull/12161) ([kickoke](https://github.com/kickoke))
- Update packaging CI to only run a limited set of jobs on PRs. [\#12156](https://github.com/netdata/netdata/pull/12156) ([Ferroin](https://github.com/Ferroin))
- kickstart.sh: fix quoting for globbing [\#12148](https://github.com/netdata/netdata/pull/12148) ([fayak](https://github.com/fayak))
- Remove backends subsystem [\#12146](https://github.com/netdata/netdata/pull/12146) ([vlvkobal](https://github.com/vlvkobal))
- Removed Google Analytics from the docs [\#12145](https://github.com/netdata/netdata/pull/12145) ([kickoke](https://github.com/kickoke))
- Docs: Improved kickstart's cloud installation docs [\#12143](https://github.com/netdata/netdata/pull/12143) ([kickoke](https://github.com/kickoke))
- Documentation: Fixed broken links [\#12142](https://github.com/netdata/netdata/pull/12142) ([kickoke](https://github.com/kickoke))
- Fix typo in ZFS ARC Cache size info [\#12138](https://github.com/netdata/netdata/pull/12138) ([dvdmuckle](https://github.com/dvdmuckle))
- Fix data query option allow\_past to correctly work in memory mode ram and save [\#12136](https://github.com/netdata/netdata/pull/12136) ([stelfrag](https://github.com/stelfrag))
- Improve messaging around unknown install handling in kickstart script. [\#12134](https://github.com/netdata/netdata/pull/12134) ([Ferroin](https://github.com/Ferroin))
- Fix the format=array output in context queries [\#12129](https://github.com/netdata/netdata/pull/12129) ([stelfrag](https://github.com/stelfrag))
- rename DO\_NOT\_TRACK to DISABLE\_TELEMETRY [\#12126](https://github.com/netdata/netdata/pull/12126) ([ilyam8](https://github.com/ilyam8))
- Bump follow-redirects from 1.14.7 to 1.14.8 [\#12124](https://github.com/netdata/netdata/pull/12124) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump karma from 6.0.2 to 6.3.14 [\#12116](https://github.com/netdata/netdata/pull/12116) ([dependabot[bot]](https://github.com/apps/dependabot))
- Track anomaly rates with DBEngine. [\#12083](https://github.com/netdata/netdata/pull/12083) ([vkalintiris](https://github.com/vkalintiris))
- Fix compilation warnings on macOS [\#12082](https://github.com/netdata/netdata/pull/12082) ([vlvkobal](https://github.com/vlvkobal))
- feat\(apps.plugin\): group Apple Filing Protocol daemons into `afp` group [\#12078](https://github.com/netdata/netdata/pull/12078) ([ilyam8](https://github.com/ilyam8))
- Overhaul handling of auto-updates in the installer code. [\#12076](https://github.com/netdata/netdata/pull/12076) ([Ferroin](https://github.com/Ferroin))
- Add serial numbers to chart names [\#12067](https://github.com/netdata/netdata/pull/12067) ([vlvkobal](https://github.com/vlvkobal))
- remove deprecated node.d modules [\#12047](https://github.com/netdata/netdata/pull/12047) ([ilyam8](https://github.com/ilyam8))
- Remove SIZEOF\_VOIDP and ENVIRONMENT{32,64} macros. [\#12046](https://github.com/netdata/netdata/pull/12046) ([vkalintiris](https://github.com/vkalintiris))
- Remove unused NETDATA\_NO\_ATOMIC\_INSTRUCTIONS macro [\#12045](https://github.com/netdata/netdata/pull/12045) ([vkalintiris](https://github.com/vkalintiris))
- Remove NETDATA\_WITH\_UUID def because it's not used anywhere. [\#12044](https://github.com/netdata/netdata/pull/12044) ([vkalintiris](https://github.com/vkalintiris))
- inform cloud about inability to satisfy request [\#12041](https://github.com/netdata/netdata/pull/12041) ([underhood](https://github.com/underhood))
- adds install method to /api/v1/info as label [\#12040](https://github.com/netdata/netdata/pull/12040) ([underhood](https://github.com/underhood))
- Stream compression - Deactivate compression at runtime in case of a compressor buffer overflow [\#12037](https://github.com/netdata/netdata/pull/12037) ([odynik](https://github.com/odynik))
- Adds all query types to aclk\_processed\_query\_type [\#12036](https://github.com/netdata/netdata/pull/12036) ([underhood](https://github.com/underhood))
- Create a removed alert event if chart goes obsolete [\#12021](https://github.com/netdata/netdata/pull/12021) ([MrZammler](https://github.com/MrZammler))
- minor - remove ACLK\_NEWARCH\_DEVMODE [\#12018](https://github.com/netdata/netdata/pull/12018) ([underhood](https://github.com/underhood))
- Adds chart for incoming proto msgs in new cloud protocol [\#11969](https://github.com/netdata/netdata/pull/11969) ([underhood](https://github.com/underhood))
- Update AWS SNS README.md [\#11946](https://github.com/netdata/netdata/pull/11946) ([kickoke](https://github.com/kickoke))
- Add `--no-same-owner` to `tar xf` in installer [\#11940](https://github.com/netdata/netdata/pull/11940) ([cimnine](https://github.com/cimnine))

## [v1.33.1](https://github.com/netdata/netdata/tree/v1.33.1) (2022-02-14)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.33.0...v1.33.1)

**Merged pull requests:**

- docs: rename kickstart install badges units [\#12131](https://github.com/netdata/netdata/pull/12131) ([ilyam8](https://github.com/ilyam8))
- Update dashboard to version v2.20.18. [\#12117](https://github.com/netdata/netdata/pull/12117) ([netdatabot](https://github.com/netdatabot))
- Docs: Fix paths to install boxes [\#12109](https://github.com/netdata/netdata/pull/12109) ([kickoke](https://github.com/kickoke))
- Docs fix: Match the new install box component name [\#12106](https://github.com/netdata/netdata/pull/12106) ([kickoke](https://github.com/kickoke))
- Add proper support for Oracle Linux native packages to installer. [\#12101](https://github.com/netdata/netdata/pull/12101) ([Ferroin](https://github.com/Ferroin))
- Docs improvement: Added interactive kickstart scripts where possible [\#12098](https://github.com/netdata/netdata/pull/12098) ([kickoke](https://github.com/kickoke))
- Update syntax for Caddy v2 [\#12092](https://github.com/netdata/netdata/pull/12092) ([mohammed90](https://github.com/mohammed90))
- Properly handle non-interactive installs as non-root users. [\#12089](https://github.com/netdata/netdata/pull/12089) ([Ferroin](https://github.com/Ferroin))
- Add info about installer interactivity to anonymous installer telemetry events. [\#12088](https://github.com/netdata/netdata/pull/12088) ([Ferroin](https://github.com/Ferroin))
- Make a lack of an os-release file non-fatal on install. [\#12087](https://github.com/netdata/netdata/pull/12087) ([Ferroin](https://github.com/Ferroin))
- docs: add a note that the "Install Netdata on Synology" is maintained by community [\#12086](https://github.com/netdata/netdata/pull/12086) ([ilyam8](https://github.com/ilyam8))
- disable\_ebpf\_socket: Disable thread while race condition is fixed [\#12085](https://github.com/netdata/netdata/pull/12085) ([thiagoftsm](https://github.com/thiagoftsm))
- add native installation for rockylinux [\#12081](https://github.com/netdata/netdata/pull/12081) ([maneamarius](https://github.com/maneamarius))
- Remove mention of libJudy in installation documentation for macOS [\#12080](https://github.com/netdata/netdata/pull/12080) ([vlvkobal](https://github.com/vlvkobal))
- docs: improve "Docker container names resolution" section [\#12079](https://github.com/netdata/netdata/pull/12079) ([ilyam8](https://github.com/ilyam8))
- Fix aclk\_kill\_link reconnect endless loop [\#12074](https://github.com/netdata/netdata/pull/12074) ([underhood](https://github.com/underhood))
- Disable hashes for charts and alerts if openssl is not available [\#12071](https://github.com/netdata/netdata/pull/12071) ([MrZammler](https://github.com/MrZammler))
- Adds legacy protocol deprecation banner to agent log [\#12065](https://github.com/netdata/netdata/pull/12065) ([underhood](https://github.com/underhood))
- fix typo, tidy up sentence [\#12062](https://github.com/netdata/netdata/pull/12062) ([petecooper](https://github.com/petecooper))
- Docs install cleanup [\#12057](https://github.com/netdata/netdata/pull/12057) ([kickoke](https://github.com/kickoke))
- Fix handling of non-x86 static builds in updater. [\#12055](https://github.com/netdata/netdata/pull/12055) ([Ferroin](https://github.com/Ferroin))
- fix\(docs\): unresolved file references [\#12053](https://github.com/netdata/netdata/pull/12053) ([ilyam8](https://github.com/ilyam8))
- Update dashboard to version v2.20.16. [\#12052](https://github.com/netdata/netdata/pull/12052) ([netdatabot](https://github.com/netdatabot))
- \[Stream Compression\] - Bug fix \#12043 - lz4.h compilation error - compile from source [\#12049](https://github.com/netdata/netdata/pull/12049) ([odynik](https://github.com/odynik))
- Fix compilation errors for OpenSSL on macOS [\#12048](https://github.com/netdata/netdata/pull/12048) ([vlvkobal](https://github.com/vlvkobal))
- Updated the docs to match new install script [\#12042](https://github.com/netdata/netdata/pull/12042) ([kickoke](https://github.com/kickoke))
- Fix handling of removed packages with leftover config files in package check. [\#12033](https://github.com/netdata/netdata/pull/12033) ([Ferroin](https://github.com/Ferroin))
- update existing OS dependencies scripts and add scripts for fedora an… [\#11963](https://github.com/netdata/netdata/pull/11963) ([maneamarius](https://github.com/maneamarius))
- Posix [\#11961](https://github.com/netdata/netdata/pull/11961) ([maneamarius](https://github.com/maneamarius))
- Updated formatting issues and copy [\#11944](https://github.com/netdata/netdata/pull/11944) ([kickoke](https://github.com/kickoke))

## [v1.33.0](https://github.com/netdata/netdata/tree/v1.33.0) (2022-01-26)

[Full Changelog](https://github.com/netdata/netdata/compare/1.32.1...v1.33.0)

**Merged pull requests:**

- Re-instate plugins\_action for clabels [\#12039](https://github.com/netdata/netdata/pull/12039) ([MrZammler](https://github.com/MrZammler))
- Have cURL properly fail on non-2xx status codes in the installer. [\#12038](https://github.com/netdata/netdata/pull/12038) ([Ferroin](https://github.com/Ferroin))
- Docs Bugfix: Fixed Markdown formatting [\#12026](https://github.com/netdata/netdata/pull/12026) ([kickoke](https://github.com/kickoke))
- update README [\#12024](https://github.com/netdata/netdata/pull/12024) ([cboydstun](https://github.com/cboydstun))
- \[Stream Compression\] - Compressor buffer overflow causes stream corruption. [\#12019](https://github.com/netdata/netdata/pull/12019) ([odynik](https://github.com/odynik))
- mqtt\_websockets submodule to latest master \(fix \#12011\) [\#12015](https://github.com/netdata/netdata/pull/12015) ([underhood](https://github.com/underhood))
- Remove uncessary call [\#12014](https://github.com/netdata/netdata/pull/12014) ([thiagoftsm](https://github.com/thiagoftsm))
- Updated idlejitter-plugin docs [\#12012](https://github.com/netdata/netdata/pull/12012) ([kickoke](https://github.com/kickoke))
- Add install type info to `-W buildinfo` output. [\#12010](https://github.com/netdata/netdata/pull/12010) ([Ferroin](https://github.com/Ferroin))
- Remove internal dbengine header from spawn/spawn\_client.c [\#12009](https://github.com/netdata/netdata/pull/12009) ([vkalintiris](https://github.com/vkalintiris))
- Fix typo in the dashboard\_info.js spigot part [\#12008](https://github.com/netdata/netdata/pull/12008) ([lokerhp](https://github.com/lokerhp))
- Add support for NVME disks with blkext driver [\#12007](https://github.com/netdata/netdata/pull/12007) ([ralphm](https://github.com/ralphm))
- Fix cleanup from a failed DEB install. [\#12006](https://github.com/netdata/netdata/pull/12006) ([Ferroin](https://github.com/Ferroin))
- update go.d.plugin version to v0.31.2 [\#12005](https://github.com/netdata/netdata/pull/12005) ([ilyam8](https://github.com/ilyam8))
- Fix handling of static archive selection for installs. [\#12004](https://github.com/netdata/netdata/pull/12004) ([Ferroin](https://github.com/Ferroin))
- fix\(python.d.plugin\): prefer python3 if available [\#12001](https://github.com/netdata/netdata/pull/12001) ([ilyam8](https://github.com/ilyam8))
- Fixing redirects [\#12000](https://github.com/netdata/netdata/pull/12000) ([kickoke](https://github.com/kickoke))
- Fix install prefix handling for claiming code in new kickstart script. [\#11999](https://github.com/netdata/netdata/pull/11999) ([Ferroin](https://github.com/Ferroin))
- Add alternative install command for macOS. [\#11997](https://github.com/netdata/netdata/pull/11997) ([Ferroin](https://github.com/Ferroin))
- Fix queue removed alerts [\#11996](https://github.com/netdata/netdata/pull/11996) ([MrZammler](https://github.com/MrZammler))
- update go.d.plugin version to v0.31.1 [\#11995](https://github.com/netdata/netdata/pull/11995) ([ilyam8](https://github.com/ilyam8))
- Fix ib counters [\#11994](https://github.com/netdata/netdata/pull/11994) ([Saruspete](https://github.com/Saruspete))
- eBPF plugin CO-RE and monitoring [\#11992](https://github.com/netdata/netdata/pull/11992) ([thiagoftsm](https://github.com/thiagoftsm))
- Included link to charts.d example [\#11990](https://github.com/netdata/netdata/pull/11990) ([kickoke](https://github.com/kickoke))
- Refined the python example for clarity [\#11989](https://github.com/netdata/netdata/pull/11989) ([kickoke](https://github.com/kickoke))
- fix\(updater\): checksum validation for static build [\#11986](https://github.com/netdata/netdata/pull/11986) ([ilyam8](https://github.com/ilyam8))
- fix\(python.d\): ignore decoding errors in ExecutableService [\#11979](https://github.com/netdata/netdata/pull/11979) ([ilyam8](https://github.com/ilyam8))
- Deleted duplicate getting started doc [\#11978](https://github.com/netdata/netdata/pull/11978) ([kickoke](https://github.com/kickoke))
- Bump lodash from 4.17.19 to 4.17.21 [\#11976](https://github.com/netdata/netdata/pull/11976) ([dependabot[bot]](https://github.com/apps/dependabot))
- Better handle creation of UUID for claiming. [\#11974](https://github.com/netdata/netdata/pull/11974) ([Ferroin](https://github.com/Ferroin))
- Fixes coverity 374746 [\#11973](https://github.com/netdata/netdata/pull/11973) ([MrZammler](https://github.com/MrZammler))
- Bump follow-redirects from 1.13.2 to 1.14.7 [\#11972](https://github.com/netdata/netdata/pull/11972) ([dependabot[bot]](https://github.com/apps/dependabot))
- Use libnetdata/required\_dummies.h in collectors. [\#11971](https://github.com/netdata/netdata/pull/11971) ([vkalintiris](https://github.com/vkalintiris))
- Fixes Wrong Chart Description [\#11970](https://github.com/netdata/netdata/pull/11970) ([underhood](https://github.com/underhood))
- Bump engine.io from 4.1.0 to 4.1.2 [\#11968](https://github.com/netdata/netdata/pull/11968) ([dependabot[bot]](https://github.com/apps/dependabot))
- Do not use dbengine headers when dbengine is disabled. [\#11967](https://github.com/netdata/netdata/pull/11967) ([vkalintiris](https://github.com/vkalintiris))
- Perform a host metadata update on child reconnection [\#11965](https://github.com/netdata/netdata/pull/11965) ([stelfrag](https://github.com/stelfrag))
- Remove bitfields from rrdhost. [\#11964](https://github.com/netdata/netdata/pull/11964) ([vkalintiris](https://github.com/vkalintiris))
- Update libmongoc CMake config [\#11962](https://github.com/netdata/netdata/pull/11962) ([vlvkobal](https://github.com/vlvkobal))
- Find host and pass host-\>health\_enabled to cloud AlarmLogHealth message [\#11960](https://github.com/netdata/netdata/pull/11960) ([MrZammler](https://github.com/MrZammler))
- Updated SNMP v3 documentation [\#11959](https://github.com/netdata/netdata/pull/11959) ([kickoke](https://github.com/kickoke))
- Add a missing capability for the perf plugin [\#11958](https://github.com/netdata/netdata/pull/11958) ([vlvkobal](https://github.com/vlvkobal))
- python.d/nvidia\_smi: add bar1 chart [\#11956](https://github.com/netdata/netdata/pull/11956) ([pbouchez](https://github.com/pbouchez))
- Compute platform-specific list of static\_threads at runtime. [\#11955](https://github.com/netdata/netdata/pull/11955) ([vkalintiris](https://github.com/vkalintiris))
- fix\(nfacct.plugin\): Netfilter accounting charts priority [\#11952](https://github.com/netdata/netdata/pull/11952) ([ilyam8](https://github.com/ilyam8))
- fix\(nfacct.plugin\): Netfilter accounting data collection [\#11951](https://github.com/netdata/netdata/pull/11951) ([ilyam8](https://github.com/ilyam8))
- fix: add a note that netfilter's `new` and `ignore` counters are removed in the latest kernel [\#11950](https://github.com/netdata/netdata/pull/11950) ([ilyam8](https://github.com/ilyam8))
- Fix a broken link in dashboard\_info.js [\#11948](https://github.com/netdata/netdata/pull/11948) ([Ancairon](https://github.com/Ancairon))
- fix retrieving service commands without failure [\#11947](https://github.com/netdata/netdata/pull/11947) ([maneamarius](https://github.com/maneamarius))
- Fix yum config-manager check [\#11945](https://github.com/netdata/netdata/pull/11945) ([lgrn](https://github.com/lgrn))
- Fixed formatting [\#11943](https://github.com/netdata/netdata/pull/11943) ([kickoke](https://github.com/kickoke))
- Fix error in configure.ac [\#11937](https://github.com/netdata/netdata/pull/11937) ([underhood](https://github.com/underhood))
- Update dashboard to version v2.20.15. [\#11934](https://github.com/netdata/netdata/pull/11934) ([netdatabot](https://github.com/netdatabot))
- Blocking publish and in flight buffer regrowth [\#11932](https://github.com/netdata/netdata/pull/11932) ([underhood](https://github.com/underhood))
- Try to find worker config thread from inactive threads for new architecture [\#11928](https://github.com/netdata/netdata/pull/11928) ([MrZammler](https://github.com/MrZammler))
- Handle re-claim while the agent is running in new architecture [\#11924](https://github.com/netdata/netdata/pull/11924) ([MrZammler](https://github.com/MrZammler))
- fix\(claim\): set URL\_BASE only if `-url` parameter value is not null [\#11919](https://github.com/netdata/netdata/pull/11919) ([ilyam8](https://github.com/ilyam8))
- Include libatomic again to allow protobuf to resolve [\#11917](https://github.com/netdata/netdata/pull/11917) ([MrZammler](https://github.com/MrZammler))
- Send ML feature information with UpdateNodeInfo. [\#11913](https://github.com/netdata/netdata/pull/11913) ([vkalintiris](https://github.com/vkalintiris))
- Don’t verify optional dependencies in build test environments in CI. [\#11910](https://github.com/netdata/netdata/pull/11910) ([Ferroin](https://github.com/Ferroin))
- fix getting latest release tag [\#11908](https://github.com/netdata/netdata/pull/11908) ([maneamarius](https://github.com/maneamarius))
- Added "==" to the list of expression operators [\#11905](https://github.com/netdata/netdata/pull/11905) ([laned130](https://github.com/laned130))
- fix\(docs\): unresolved file references [\#11903](https://github.com/netdata/netdata/pull/11903) ([ilyam8](https://github.com/ilyam8))
- Fix slight errors [\#11902](https://github.com/netdata/netdata/pull/11902) ([ardabbour](https://github.com/ardabbour))
- Fix time\_t format [\#11897](https://github.com/netdata/netdata/pull/11897) ([vlvkobal](https://github.com/vlvkobal))
- Fix handling of agent restart on update. [\#11887](https://github.com/netdata/netdata/pull/11887) ([Ferroin](https://github.com/Ferroin))
- Provide runtime ml info from a new endpoint. [\#11886](https://github.com/netdata/netdata/pull/11886) ([vkalintiris](https://github.com/vkalintiris))
- fix permissions of plugins that may be built [\#11877](https://github.com/netdata/netdata/pull/11877) ([boxjan](https://github.com/boxjan))
- Use absolute features when doing training/prediction. [\#11876](https://github.com/netdata/netdata/pull/11876) ([vkalintiris](https://github.com/vkalintiris))
- Update dependencies for the pubsub exporting connector [\#11872](https://github.com/netdata/netdata/pull/11872) ([vlvkobal](https://github.com/vlvkobal))
- Fix the code that checks for available updates. [\#11870](https://github.com/netdata/netdata/pull/11870) ([Ferroin](https://github.com/Ferroin))
- Don't check for symbols in libaws-cpp-sdk-core [\#11867](https://github.com/netdata/netdata/pull/11867) ([vlvkobal](https://github.com/vlvkobal))
- ACLK-NG remove 'cmd' switch by message type [\#11866](https://github.com/netdata/netdata/pull/11866) ([underhood](https://github.com/underhood))
- Update libbpf [\#11865](https://github.com/netdata/netdata/pull/11865) ([thiagoftsm](https://github.com/thiagoftsm))
- Fix cmake build [\#11862](https://github.com/netdata/netdata/pull/11862) ([vlvkobal](https://github.com/vlvkobal))
- chore: update community link of alert notifications [\#11860](https://github.com/netdata/netdata/pull/11860) ([burbuli8ra](https://github.com/burbuli8ra))

## [1.32.1](https://github.com/netdata/netdata/tree/1.32.1) (2021-12-14)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.32.1...1.32.1)

## [v1.32.1](https://github.com/netdata/netdata/tree/v1.32.1) (2021-12-14)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.32.0...v1.32.1)

**Merged pull requests:**

- Clean up anomaly-detection guide docs [\#11901](https://github.com/netdata/netdata/pull/11901) ([andrewm4894](https://github.com/andrewm4894))
- Use the chart id instead of chart name in response to incoming cloud context queries [\#11898](https://github.com/netdata/netdata/pull/11898) ([stelfrag](https://github.com/stelfrag))
- Moved data privacy section into a separate topic [\#11889](https://github.com/netdata/netdata/pull/11889) ([kickoke](https://github.com/kickoke))
- Fixed formatting issues. [\#11888](https://github.com/netdata/netdata/pull/11888) ([kickoke](https://github.com/kickoke))
- Fix postdrop handling for systemd systems. [\#11885](https://github.com/netdata/netdata/pull/11885) ([Ferroin](https://github.com/Ferroin))
- Minor ACLK docu updates [\#11882](https://github.com/netdata/netdata/pull/11882) ([underhood](https://github.com/underhood))
- Adds Swagger docs for new `/api/v1/aclk` endpoint [\#11881](https://github.com/netdata/netdata/pull/11881) ([underhood](https://github.com/underhood))
- fix\(updater\): don't produce output when static update succeeded [\#11879](https://github.com/netdata/netdata/pull/11879) ([ilyam8](https://github.com/ilyam8))
- fix\(updater\): fix exit code when updating static install && updater script [\#11873](https://github.com/netdata/netdata/pull/11873) ([ilyam8](https://github.com/ilyam8))
- add z score alarm example [\#11871](https://github.com/netdata/netdata/pull/11871) ([andrewm4894](https://github.com/andrewm4894))
- fix\(health\): used\_swap alarm calc [\#11868](https://github.com/netdata/netdata/pull/11868) ([ilyam8](https://github.com/ilyam8))

## [v1.32.0](https://github.com/netdata/netdata/tree/v1.32.0) (2021-11-30)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.31.0...v1.32.0)

## [v1.31.0](https://github.com/netdata/netdata/tree/v1.31.0) (2021-05-19)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.30.1...v1.31.0)

## [v1.30.1](https://github.com/netdata/netdata/tree/v1.30.1) (2021-04-12)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.30.0...v1.30.1)

## [v1.30.0](https://github.com/netdata/netdata/tree/v1.30.0) (2021-03-31)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.29.3...v1.30.0)

## [v1.29.3](https://github.com/netdata/netdata/tree/v1.29.3) (2021-02-23)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.29.2...v1.29.3)

## [v1.29.2](https://github.com/netdata/netdata/tree/v1.29.2) (2021-02-18)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.29.1...v1.29.2)

## [v1.29.1](https://github.com/netdata/netdata/tree/v1.29.1) (2021-02-09)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.29.0...v1.29.1)

## [v1.29.0](https://github.com/netdata/netdata/tree/v1.29.0) (2021-02-03)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.27.0_0104103941...v1.29.0)

## [v1.27.0_0104103941](https://github.com/netdata/netdata/tree/v1.27.0_0104103941) (2021-01-04)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.28.0...v1.27.0_0104103941)

## [v1.28.0](https://github.com/netdata/netdata/tree/v1.28.0) (2020-12-18)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.27.0...v1.28.0)

## [v1.27.0](https://github.com/netdata/netdata/tree/v1.27.0) (2020-12-17)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.26.0...v1.27.0)

## [v1.26.0](https://github.com/netdata/netdata/tree/v1.26.0) (2020-10-14)

[Full Changelog](https://github.com/netdata/netdata/compare/before_rebase...v1.26.0)

## [before_rebase](https://github.com/netdata/netdata/tree/before_rebase) (2020-09-24)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.25.0...before_rebase)

## [v1.25.0](https://github.com/netdata/netdata/tree/v1.25.0) (2020-09-15)

[Full Changelog](https://github.com/netdata/netdata/compare/poc2...v1.25.0)

## [poc2](https://github.com/netdata/netdata/tree/poc2) (2020-08-25)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.24.0...poc2)

## [v1.24.0](https://github.com/netdata/netdata/tree/v1.24.0) (2020-08-10)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.23.2...v1.24.0)

## [v1.23.2](https://github.com/netdata/netdata/tree/v1.23.2) (2020-07-16)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.23.1...v1.23.2)

## [v1.23.1](https://github.com/netdata/netdata/tree/v1.23.1) (2020-07-01)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.23.0...v1.23.1)

## [v1.23.0](https://github.com/netdata/netdata/tree/v1.23.0) (2020-06-25)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.22.1...v1.23.0)

## [v1.22.1](https://github.com/netdata/netdata/tree/v1.22.1) (2020-05-12)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.22.0...v1.22.1)

## [v1.22.0](https://github.com/netdata/netdata/tree/v1.22.0) (2020-05-11)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.21.1...v1.22.0)

## [v1.21.1](https://github.com/netdata/netdata/tree/v1.21.1) (2020-04-13)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.21.0...v1.21.1)

## [v1.21.0](https://github.com/netdata/netdata/tree/v1.21.0) (2020-04-06)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.20.0...v1.21.0)

## [v1.20.0](https://github.com/netdata/netdata/tree/v1.20.0) (2020-02-21)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.19.0...v1.20.0)

## [v1.19.0](https://github.com/netdata/netdata/tree/v1.19.0) (2019-11-27)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.18.1...v1.19.0)

## [v1.18.1](https://github.com/netdata/netdata/tree/v1.18.1) (2019-10-18)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.18.0...v1.18.1)

## [v1.18.0](https://github.com/netdata/netdata/tree/v1.18.0) (2019-10-10)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.17.1...v1.18.0)

## [v1.17.1](https://github.com/netdata/netdata/tree/v1.17.1) (2019-09-12)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.17.0...v1.17.1)

## [v1.17.0](https://github.com/netdata/netdata/tree/v1.17.0) (2019-09-03)

[Full Changelog](https://github.com/netdata/netdata/compare/issue_4934...v1.17.0)

## [issue_4934](https://github.com/netdata/netdata/tree/issue_4934) (2019-08-03)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.16.1...issue_4934)

## [v1.16.1](https://github.com/netdata/netdata/tree/v1.16.1) (2019-07-31)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.16.0...v1.16.1)

## [v1.16.0](https://github.com/netdata/netdata/tree/v1.16.0) (2019-07-08)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.15.0...v1.16.0)

## [v1.15.0](https://github.com/netdata/netdata/tree/v1.15.0) (2019-05-22)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.14.0...v1.15.0)

## [v1.14.0](https://github.com/netdata/netdata/tree/v1.14.0) (2019-04-18)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.14.0-rc0...v1.14.0)

## [v1.14.0-rc0](https://github.com/netdata/netdata/tree/v1.14.0-rc0) (2019-03-30)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.13.0...v1.14.0-rc0)

## [v1.13.0](https://github.com/netdata/netdata/tree/v1.13.0) (2019-03-14)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.12.2...v1.13.0)

## [v1.12.2](https://github.com/netdata/netdata/tree/v1.12.2) (2019-02-28)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.12.1...v1.12.2)

## [v1.12.1](https://github.com/netdata/netdata/tree/v1.12.1) (2019-02-21)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.12.0...v1.12.1)

## [v1.12.0](https://github.com/netdata/netdata/tree/v1.12.0) (2019-02-06)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.12.0-rc3...v1.12.0)

## [v1.12.0-rc3](https://github.com/netdata/netdata/tree/v1.12.0-rc3) (2019-01-17)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.12.0-rc2...v1.12.0-rc3)

## [v1.12.0-rc2](https://github.com/netdata/netdata/tree/v1.12.0-rc2) (2019-01-03)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.12.0-rc1...v1.12.0-rc2)

## [v1.12.0-rc1](https://github.com/netdata/netdata/tree/v1.12.0-rc1) (2018-12-19)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.12.0-rc0...v1.12.0-rc1)

## [v1.12.0-rc0](https://github.com/netdata/netdata/tree/v1.12.0-rc0) (2018-12-06)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.11.1...v1.12.0-rc0)

## [v1.11.1](https://github.com/netdata/netdata/tree/v1.11.1) (2018-11-22)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.11.0...v1.11.1)

## [v1.11.0](https://github.com/netdata/netdata/tree/v1.11.0) (2018-11-02)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.10.0...v1.11.0)



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
