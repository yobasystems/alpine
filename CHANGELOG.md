Alpine 3.17.10, 3.18.9, 3.19.4, 3.20.3 released
The Alpine Linux project is pleased to announce the immediate availability of new stable releases:

3.17.10
3.18.9
3.19.4
3.20.3
Those releases contains various security fixes including a fix for OpenSSL CVE-2024-6119.


Alpine 3.20.2 released
We are pleased to announce the release of Alpine Linux 3.20.2, a maintenance release of the 3.20 series. This release includes various bug fixes and security updates, including a security fix with low severity for OpenSSL CVE-2024-5535

The full lists of changes can be found in the git log.

Git Shortlog

Adam Thiede (1):
      community/wmenu: upgrade to 0.1.9

Andy Postnikov (3):
      community/php82: upgrade to 8.2.21
      community/php83: upgrade to 8.3.9
      community/phpspy: upgrade to 0.7.0

Antoine Martin (6):
      community/ikiwiki: add po4a 0.7.0 support
      community/git-annex: upgrade to 10.20240701
      community/dotnet8-runtime: security upgrade to 8.0.7
      community/dotnet8-sdk: security upgrade to 8.0.107
      community/dotnet6-build: security upgrade to 6.0.132
      community/dotnet6-runtime: security upgrade to 6.0.32

Bart Ribbers (3):
      community/falkon: re-enable on armv7
      community/plasmatube: add missing dependency on qqc2-desktop-style
      community/plasmatube: add missing dependency on kitemmodels

Celeste (6):
      community/emacs: security upgrade to 29.4
      community/znc: security upgrade to 1.9.1
      community/helm: fix tests
      community/exiv2: security upgrade to 0.28.3
      community/qpdf: upgrade to 11.9.1
      community/ktistec: upgrade to 2.1.0

Daniel Néri (3):
      main/py3-requests: security upgrade to 2.32.3
      community/mercurial: upgrade to 6.7.4
      community/soju: upgrade to 0.8.1

David Heidelberg (1):
      main/mesa: upgrade to 24.0.9

Duncan Bellamy (1):
      community/dovecot-fts-xapian: upgrade to 1.7.13

Francesco Colista (1):
      community/py3-docker-py: upgrade to 7.1.0

Henrik Grimler (2):
      community/heimdall: backport patch from v2.1.0 to fix segfault
      community/heimdall: upgrade to 2.1.0

Henrik Riomar (1):
      community/py3-pydantic-settings: new aport

Holger Jaekel (1):
      community/gdal: upgrade to 3.9.1

J0WI (7):
      main/openssl: patch CVE-2024-5535
      main/krb5: security upgrade to 1.21.3
      main/apache2: security upgrade to 2.4.60
      main/ghostscript: security upgrade to 10.03.1
      community/exim: security upgrade to 4.98
      community/qpdf: update secfixes
      main/apache2: security upgrade to 2.4.62

Jakub Jirutka (3):
      main/ruby-rexml: upgrade to 3.2.9
      main/ruby: upgrade to 3.3.3
      community/keycloak: rebuild

Jonathan Schleifer (1):
      [3.20] community/objfw: upgrade to 1.1.5

Kevin Daudt (3):
      main/py3-requests: fix secfixes
      main/openvpn: security upgrade to 2.6.11
      main/ca-certificates: upgrade to 20240705

Krassy Boykinov (4):
      community/libdex: upgrade to 0.6.1
      community/libpeas2: upgrade to 2.0.3
      community/gexiv2: upgrade to 0.14.3
      community/libadwaita: upgrade to 1.5.2

Michał Polański (2):
      community/soju: move from testing
      community/borgmatic: upgrade to 1.8.13

Milan P. Stanić (4):
      community/linux-edge: upgrade to 6.9.6
      community/linux-edge: upgrade to 6.9.7
      community/linux-edge: upgrade to 6.9.8
      community/linux-edge: upgrade to 6.9.9

Natanael Copa (70):
      community/virt-manager: backport fix for virt-install
      main/linux-lts: upgrade to 6.6.35
      community/jool-modules-lts: rebuild against kernel 6.6.35-r0
      community/rtpengine-lts: rebuild against kernel 6.6.35-r0
      community/virtio_vmmci-lts: rebuild against kernel 6.6.35-r0
      community/vmm_clock-lts: rebuild against kernel 6.6.35-r0
      main/xtables-addons-lts: rebuild against kernel 6.6.35-r0
      main/zfs-lts: rebuild against kernel 6.6.35-r0
      main/nghttp2: upgrade to 1.62.1
      main/linux-lts: enablel SLUB debug
      main/linux-lts: upgrade to 6.6.36
      community/jool-modules-lts: rebuild against kernel 6.6.36-r0
      community/rtpengine-lts: rebuild against kernel 6.6.36-r0
      community/virtio_vmmci-lts: rebuild against kernel 6.6.36-r0
      community/vmm_clock-lts: rebuild against kernel 6.6.36-r0
      main/xtables-addons-lts: rebuild against kernel 6.6.36-r0
      main/zfs-lts: rebuild against kernel 6.6.36-r0
      community/osinfo-db: upgrade to 20240701
      main/apache2: security upgrade to 2.4.61 (CVE-2024-39884)
      main/linux-lts: upgrade to 6.6.37
      community/jool-modules-lts: rebuild against kernel 6.6.37-r0
      community/rtpengine-lts: rebuild against kernel 6.6.37-r0
      community/virtio_vmmci-lts: rebuild against kernel 6.6.37-r0
      community/vmm_clock-lts: rebuild against kernel 6.6.37-r0
      main/xtables-addons-lts: rebuild against kernel 6.6.37-r0
      main/zfs-lts: rebuild against kernel 6.6.37-r0
      community/jool-modules-lts: rebuild against kernel 6.6.37-r1
      community/rtpengine-lts: rebuild against kernel 6.6.37-r1
      community/virtio_vmmci-lts: rebuild against kernel 6.6.37-r1
      community/vmm_clock-lts: rebuild against kernel 6.6.37-r1
      main/xtables-addons-lts: rebuild against kernel 6.6.37-r1
      main/zfs-lts: rebuild against kernel 6.6.37-r1
      main/linux-lts: upgrade to 6.6.38
      community/jool-modules-lts: rebuild against kernel 6.6.38-r0
      community/rtpengine-lts: rebuild against kernel 6.6.38-r0
      community/virtio_vmmci-lts: rebuild against kernel 6.6.38-r0
      community/vmm_clock-lts: rebuild against kernel 6.6.38-r0
      main/xtables-addons-lts: rebuild against kernel 6.6.38-r0
      main/zfs-lts: rebuild against kernel 6.6.38-r0
      main/linux-lts: upgrade to 6.6.39
      community/jool-modules-lts: rebuild against kernel 6.6.39-r0
      community/rtpengine-lts: rebuild against kernel 6.6.39-r0
      community/virtio_vmmci-lts: rebuild against kernel 6.6.39-r0
      community/vmm_clock-lts: rebuild against kernel 6.6.39-r0
      main/xtables-addons-lts: rebuild against kernel 6.6.39-r0
      main/zfs-lts: rebuild against kernel 6.6.39-r0
      community/jfsutils: fix use of basename
      community/py3-nose: add cpython license
      main/awall: backport fix for legacy compat
      main/linux-lts: upgrade to 6.6.40
      community/jool-modules-lts: rebuild against kernel 6.6.40-r0
      community/rtpengine-lts: rebuild against kernel 6.6.40-r0
      community/virtio_vmmci-lts: rebuild against kernel 6.6.40-r0
      community/vmm_clock-lts: rebuild against kernel 6.6.40-r0
      main/xtables-addons-lts: rebuild against kernel 6.6.40-r0
      main/zfs-lts: rebuild against kernel 6.6.40-r0
      main/linux-rpi: upgrade to 6.6.41
      community/jool-modules-rpi: rebuild against kernel 6.6.41-r0
      main/xtables-addons-rpi: rebuild against kernel 6.6.41-r0
      main/zfs-rpi: rebuild against kernel 6.6.41-r0
      main/linux-lts: enable drivers for v86 in -virt
      main/linux-lts: upgrade to 6.6.41
      community/jool-modules-lts: rebuild against kernel 6.6.41-r0
      community/rtpengine-lts: rebuild against kernel 6.6.41-r0
      community/virtio_vmmci-lts: rebuild against kernel 6.6.41-r0
      community/vmm_clock-lts: rebuild against kernel 6.6.41-r0
      main/xtables-addons-lts: rebuild against kernel 6.6.41-r0
      main/zfs-lts: rebuild against kernel 6.6.41-r0
      main/raspberrypi-bootloader: bump to 2024-07-16
      ===== release 3.20.2 =====

Patrycja Rosa (1):
      community/qemu: fix liburing detection

Sertonix (1):
      main/linux-lts: fix KBUILD_BUILD_TIMESTAMP not parsable by busybox date

Simon Frankenberger (4):
      community/plantuml: enable aarch64 and fix build
      community/openjdk11: security upgrade to 11.0.24
      community/openjdk17: security upgrade to 17.0.12
      community/openjdk21: security upgrade to 21.0.4

Sören Tempel (4):
      community/go: upgrade to 1.22.5
      community/*: rebuild with Go 1.22.5
      community/quota-tools: fix implicit basename declaration
      community/connman: fix implicit basename(3) declaration

adamthiede (1):
      [3.20] community/reader: upgrade to 0.4.5

fossdd (7):
      main/pcsc-lite: upgrade to 2.2.3
      community/gmobile: upgrade to 0.2.1
      community/jellyfin-web: upgrade to 10.9.6
      community/jellyfin: upgrade to 10.9.6
      main/curl: upgrade to 8.8.0
      community/arti: upgrade to 1.2.5
      community/wlroots: upgrade to 0.17.4

jahway603 (5):
      [3.20] community/nextcloud: upgrade to 29.0.3
      [3.20] community/nextcloud28: upgrade to 28.0.7
      community/synapse: upgrade to 1.110.0
      community/nextcloud: upgrade to 29.0.4
      community/nextcloud28: upgrade to 28.0.8

lauren n. liberda (10):
      community/chromium: upgrade to 125.0.6422.141
      main/openssh: hotfix recent security vulneribilities
      community/chromium: upgrade to 126.0.6478.126
      community/yt-dlp: upgrade to 2024.07.02
      community/yt-dlp: upgrade to 2024.07.07
      community/yt-dlp: upgrade to 2024.07.08
      community/yt-dlp: upgrade to 2024.07.09
      main/nodejs: upgrade to 20.15.1
      community/yt-dlp: upgrade to 2024.07.16
      community/chromium: upgrade to 126.0.6478.182

oxpa (1):
      main/openssl: backport fix for a regression breaking FIPS

psykose (1):
      main/openssl: use the auxv cpu detection variant on ppc/s390x/arm

ptrcnull (2):
      main/nss: upgrade to 3.101
      community/firefox-esr: upgrade to 115.12.0

streaksu (8):
      community/limine: upgrade to 7.8.0
      community/limine: upgrade to 7.9.0
      community/limine: upgrade to 7.9.1
      community/limine: upgrade to 7.9.2
      community/limine: upgrade to 7.10.1
      community/limine: upgrade to 7.10.2
      community/limine: upgrade to 7.10.3
      community/limine: upgrade to 7.11.0

wesley van tilburg (1):
      [3.20] community/minify: upgrade to 2.20.37

Štěpán Pechman (1):
      community/gitlab-runner: upgrade to v16.11.2

Alpine 3.17.9, 3.18.8 and 3.19.3 released
The Alpine Linux project is pleased to announce the immediate availability of new stable releases:

3.17.9
3.18.8
3.19.3
Those releases contains various security fixes including a fix for OpenSSL CVE-2024-5535.


Alpine 3.20.1 released
We are pleased to announce the release of Alpine Linux 3.20.1, a maintenance release of the 3.20 series. This release includes various bug fixes and security updates, including security fixes for:

OpenSSL
CVE-2024-4741
busybox
CVE-2023-42364
CVE-2023-42365
The full lists of changes can be found in the git log.

Git Shortlog

Alex (1):
      community/dolphin-emu: upgrade to 5.0_git20240429

Andy Postnikov (9):
      community/php82-pecl-mongodb: upgrade to 1.19.1
      community/php83-pecl-mongodb: upgrade to 1.19.1
      community/php82-pecl-grpc: upgrade to 1.64.1
      community/php83-pecl-grpc: upgrade to 1.64.1
      community/php82-pecl-msgpack: fix provides #16147
      community/php83-pecl-msgpack: fix provides #16147
      community/php82: security upgrade to 8.2.20
      community/php83: security upgrade to 8.3.8
      community/composer: security upgrade to 2.7.7

Antoine Martin (6):
      community/git-annex: upgrade to 10.20240531
      community/dotnet8-runtime: upgrade to 8.0.6
      community/dotnet8-sdk: upgrade to 8.0.6
      community/dotnet6-build: upgrade to 6.0.131
      community/dotnet6-runtime: upgrade to 6.0.31
      community/py3-w3lib: upgrade to 2.2.0

Bart Ribbers (6):
      community/plasma: upgrade to 6.0.5
      community/kwidgetsaddons: upgrade to 6.2.1
      community/kwidgetsaddons: upgrade to 6.2.2
      community/kwallet: upgrade to 6.2.1
      main/dav1d: upgrade to 1.4.2
      community/plasma-workspace: upgrade to 6.0.5.1

Celeste (8):
      community/minio: upgrade to 0.20240527.191746
      community/minio-client: upgrade to 0.20240524.090849
      community/crystal: upgrade to 1.12.2
      community/imagemagick: fix perlmagick dir
      main/git: upgrade to 2.45.2
      community/libvpx: security upgrade to 1.14.1
      main/fribidi: upgrade to 1.0.15
      community/rsgain: upgrade to 3.5.1

David Heidelberg (2):
      main/mesa: upgrade to 24.0.8
      community/ffmpeg: add fixes for VA-API

Holger Jaekel (1):
      community/geos: upgrade to 3.12.2

J0WI (3):
      main/openssl: patch CVE-2024-4741
      main/openssl: upgrade to 3.3.1
      community/vlc: security upgrade to 3.0.21

Jakub Jirutka (6):
      community/neovim: don't crash if tree-sitter is not installed
      main/ruby-rbs: upgrade to 3.4.4 to fix ruby-full
      main/nginx: backport patch fixing js_set duplicate checker
      main/nginx: upgrade to 1.26.1
      community/knot-resolver: upgrade to 5.7.3
      community/keycloak: upgrade to 24.0.5

Kevin Daudt (9):
      main/valkey: move unixsocket to writable location
      community/zabbix: upgrade to 6.4.15
      community/opentofu: upgrade to 1.7.2
      community/prometheus: increase open file limit during build
      community/netdata: upgrade to 1.45.5
      community/chezmoi: upgrade to 2.48.2
      community/cs-firewall-bouncer: fix policy rules
      community/cs-firewall-bouncer: unstringify values in policy
      main/freeswitch: security upgrade to 1.10.11 (CVE-2023-51443)

Leonardo Arena (4):
      community/nextcloud: upgrade to 29.0.1
      community/incus: fix bash-completion subpkg
      community/nextcloud: upgrade to 29.0.2
      community/incus: ship simplestreams tool

Mai Thanh Minh (1):
      main/linux-lts: enable RT35XX for RT2800USB/RT2800PCI driver

Michal Tvrznik (1):
      community/emptty: upgrade to 0.12.1

Milan P. Stanić (6):
      community/linux-edge: upgrade to 6.9.2
      community/linux-edge: upgrade to 6.9.3
      community/linux-edge: upgrade to 6.9.4
      main/haproxy: upgrade to 2.8.10
      community/linux-edge: upgrade to 6.9.5
      community/qemu: upgrade to 9.0.1

Natanael Copa (40):
      main/linux-lts: upgrade to 6.6.32
      community/jool-modules-lts: rebuild against kernel 6.6.32-r0
      community/rtpengine-lts: rebuild against kernel 6.6.32-r0
      community/virtio_vmmci-lts: rebuild against kernel 6.6.32-r0
      community/vmm_clock-lts: rebuild against kernel 6.6.32-r0
      main/xtables-addons-lts: rebuild against kernel 6.6.32-r0
      main/zfs-lts: rebuild against kernel 6.6.32-r0
      main/busybox: fix CVE-2023-42364 and CVE-2023-42365
      main/yajl: fix CVE-2023-33460
      main/syslog-ng: fix c++ underlinking
      main/linux-lts: upgrade to 6.6.33
      community/jool-modules-lts: rebuild against kernel 6.6.33-r0
      community/rtpengine-lts: rebuild against kernel 6.6.33-r0
      community/virtio_vmmci-lts: rebuild against kernel 6.6.33-r0
      community/vmm_clock-lts: rebuild against kernel 6.6.33-r0
      main/xtables-addons-lts: rebuild against kernel 6.6.33-r0
      main/zfs-lts: rebuild against kernel 6.6.33-r0
      main/linux-lts: upgrade to 6.6.34
      community/jool-modules-lts: rebuild against kernel 6.6.34-r0
      community/rtpengine-lts: rebuild against kernel 6.6.34-r0
      community/virtio_vmmci-lts: rebuild against kernel 6.6.34-r0
      community/vmm_clock-lts: rebuild against kernel 6.6.34-r0
      main/xtables-addons-lts: rebuild against kernel 6.6.34-r0
      main/zfs-lts: rebuild against kernel 6.6.34-r0
      main/linux-rpi: upgrade to 6.6.34
      community/jool-modules-rpi: rebuild against kernel 6.6.34-r0
      main/xtables-addons-rpi: rebuild against kernel 6.6.34-r0
      main/zfs-rpi: rebuild against kernel 6.6.34-r0
      main/mkinitfs: upgrade to 3.10.1
      main/alpine-conf: upgrade to 3.18.1
      main/linux-lts: enable i915 GVT KVMGT module
      community/jool-modules-lts: rebuild against kernel 6.6.34-r1
      community/rtpengine-lts: rebuild against kernel 6.6.34-r1
      community/virtio_vmmci-lts: rebuild against kernel 6.6.34-r1
      community/vmm_clock-lts: rebuild against kernel 6.6.34-r1
      main/xtables-addons-lts: rebuild against kernel 6.6.34-r1
      main/zfs-lts: rebuild against kernel 6.6.34-r1
      community/qemu: fix build on riscv64
      scripts/mkimg.standard.sh: remove riscv64
      ===== release 3.20.1 =====

Oliver Smith (1):
      community/millipixels: fix libtiff 4.6.0t compat

Peter van Dijk (1):
      community/pdns: upgrade to 4.9.1

Sertonix (1):
      main/cups: security upgrade to 2.4.9 (CVE-2024-35235)

Simon Frankenberger (2):
      community/java-libsignal-client: upgrade to 0.48.0
      community/signal-cli: upgrade to 0.13.4

Stefan Hansson (3):
      community/calls: backport crash fix
      community/marknote: add missing dependencies
      community/lollypop: upgrade to 1.4.40

Sören Tempel (2):
      community/go: upgrade to 1.22.4
      community/*: rebuild with Go 1.22.4

Thomas Böhler (1):
      main/pcsc-lite: fix libusb build option

fossdd (16):
      community/aws-c-io: upgrade to 0.14.8
      community/aws-c-common: upgrade to 0.9.19
      community/aws-c-auth: upgrade to 0.7.22
      community/aws-c-s3: upgrade to 0.5.9
      community/aws-c-cal: upgrade to 0.6.14
      community/aws-c-event-stream: upgrade to 0.4.2
      community/aws-c-http: upgrade to 0.8.1
      community/aws-c-mqtt: upgrade to 0.10.4
      community/aws-c-sdkutils: upgrade to 0.1.16
      community/aws-c-compression: upgrade to 0.2.18
      community/aws-cli: enable, upgrade to 2.15.57
      main/py3-pytest: upgrade to 8.2.2
      community/tor: upgrade to 0.4.8.12
      community/phosh: include some bug fixes
      community/pipx: upgrade to 1.6.0
      community/pipx: update source url

jahway603 (1):
      community/nextcloud28: upgrade to 28.0.6

lauren n. liberda (1):
      community/chromium: security upgrade to 125.0.6422.112

macmpi (2):
      [3.20] main/raspberrypi-bootloader: upgrade to 1.20240524
      [3.20] community/raspberrypi-utils: upgrade to 0.20240523

omni (4):
      community/py3-pymysql: security upgrade to 1.1.1
      community/qt6-qtwebengine: chromium security upgrade
      community/arti: security upgrade to 1.2.4
      community/passt: upgrade to 2024.06.07

ptrcnull (4):
      main/mesa: fix crashes due to stack overflow in gl threads
      main/gawk: backport str2wstr fix
      community/firefox: upgrade to 126.0.1
      community/firefox-esr: build with system libjpeg

streaksu (5):
      community/limine: upgrade to 7.5.3
      community/limine: upgrade to 7.6.0
      community/limine: upgrade to 7.7.0
      community/limine: upgrade to 7.7.1
      community/limine: upgrade to 7.7.2

Alpine 3.17.8, 3.18.7 and 3.19.2 released
The Alpine Linux project is pleased to announce the immediate availability of new stable releases:

3.17.8
3.18.7
3.19.2
Those releases contains various security fixes including fixes for:

OpenSSL
CVE-2024-2511
CVE-2024-4603
busybox
CVE-2023-42363
CVE-2023-42364
CVE-2023-42365
CVE-2023-42366

ALPINE LINUX 3.20.0 RELEASED
We are pleased to announce the release of Alpine Linux 3.20.0, the first in the v3.20 stable series.

HIGHLIGHTS
LLVM 18
Node.js (lts) 20.10
Python 3.12
Ruby 3.3
Rust 1.78
Crystal 1.12
GNOME 46
Go 1.22
KDE 6
Sway 1.9
.NET 8.0
SIGNIFICANT CHANGES
Initial support for 64 bit RISC-V was added.

UPGRADE NOTES
As always, make sure to use apk upgrade --available when switching between major versions.

The yq package was renamed to yq-go.

CHANGES
The full list of changes can be found in the wiki, git log and bug tracker.

CREDITS
Thanks to everyone sending patches, bug reports, new and updated aports, and to everyone helping with writing documentation, maintaining the infrastructure, or contributing in any other way!

Thanks to GIGABYTE, Linode, Fastly, IBM, Equinix Metal, vpsFree and ungleich for providing us with hardware and hosting.

APORTS COMMIT CONTRIBUTORS
6543
Aaron Fischer
Adam Jensen
Adam Thiede
Adrian Siekierka
Adrián Arroyo Calle
Affe Null
Aleks Bunin
Alex Denes
Alex McGrath
Alex Xu (Hello71)
Alexey Minnekhanov
Alexey Yerin
Alistair Francis
Amelia Clarke
Andre Klitzing
Andrei Jiroh Eugenio Halili
Andrej Kolchin
Andres Almiray
André Klitzing
André Zwing
Andy Hawkins
Andy Postnikov
Anjandev Momi
Antoine Martin
Anton Bambura
Antoni Aloy Torrens
Ariadne Conill
Arnav Singh
Aron
Author: 6543
Bader Zaidan
Bart Ribbers
Biswapriyo Nath
Bobby The Builder
Boris Dolgov
Brandon Boese
Bryce Vandegrift
Carl Chave
Carlo Landmeter
Carter Li
Celeste
Chleba
Clayton Craft
Coco Liliace
Cormac Stephenson
Cory Sanin
Cowington Post
Craig Andrews
Curt Tilmes
DaKnig
Daniel Fancsali
Daniel Néri
Daniél Kerkmann
Dave Henderson
David Demelier
David Heidelberg
David Sugar
Dekedro
Dennis Krupenik
DerLinkman
Dermot Bradley
Devin Lin
Devon Thyne
Dhruvin Gandhi
Dmitry Klochkov
Dmitry Zakharchenko
Dominique Martinet
Duncan Bellamy
Díaz Urbaneja Víctor Diego Alejandro (Sodomon)
Edd Salkield
Edin Tarić
Eduardo Bart
Elly Fong-Jones
Eric Roshan-Eisner
Fabian Affolter
Fabricio Silva
Faustin Lammler
FintasticMan
Fiona Klute
FollieHiyuki
Francesco Colista
Frank Oltmanns
Fusl
Fxzx mic
Galen Abell
George Hopkins
Glenn Strauss
Guillaume Quintard
Guy Godfroy
Haelwenn (lanodan) Monnier
Hal Martin
Hannes Braun
Henrik Riomar
Hoang Nguyen
Holger Jaekel
Hugo Osvaldo Barrera
Håkan Lindqvist
Iskren Chernev
Iztok Fister Jr
Iztok Fister Jr.
J0WI
Jacob Ludvigsen
Jake Buchholz Göktürk
Jakob Hauser
Jakob Meier
Jakub Jirutka
Jakub Panek
Jaroslav Kysela
Jason Gross
Jason Staten
Jason Swank
Jeff Dickey
Jesse Mandel
Jingyun Hua
Jinming Wu, Patrick
Joel Selvaraj
Johannes Heimansberg
Johannes Marbach
John Anthony
John Gebbie
Jonas
Jonas Vautherin
Jonathan Schleifer
Jordan Christiansen
Joshua Murphy
Jules Maselbas
Julian Groß
Julie Koubova
Jurvis Tan
Justin Berthault
Kaarle Ritvanen
Kaspar Schleiser
Kevin Daudt
Khem Raj
Koni Marti
Konstantin Kulikov
Krassy Boykinov
Krystian Chachuła
Lassebq
Laurent Bercot
Leon Marz
Leon ROUX
Leonardo Arena
Lindsay Zhou
Luca Weiss
Lucidiot
Lukas Franek
Maarten van Gompel
Magnus Sandin
Marcel Steinbeck
Marco Schröder
Marian Buschsieweke
Mark Hills
Marten Ringwelski
Martijn Braam
Marvin Feldmann
Matthias Ahouansou
Michael Pirogov
Michael Truog
Michal Tvrznik
Michał Adamski
Michał Polański
Micheal Smith
Mike Crute
Milan P. Stanić
Miles Alan
Mogens Jensen
Muhammad Adeel
Natanael Copa
Nathan Angelacos
Neale Pickett
NekoCWD
NepNep21
Newbyte
Nicolas Lorin
Nik B
Niklas Meyer
Noah Zalev
Noel Kuntze
Nulo
Oleg Titov
Oliver Smith
Orhun Parmaksız
Pablo Correa Gómez
Patrick Gansterer
Paul Bredbury
Pedro Lucas Porcellis
Peter
Peter Shkenev
Peter van Dijk
Petr Vorel
Phil Estes
Philipp Arras
Qi Xiao
R4SAS
Rabindra Dhakal
Rafael Ávila de Espíndola
Rasmus Thomsen
Raymond Hackley
Ricardo Pchevuzinske Katz
RickyRockRat
Rob Blanckaert
Robert Eckelmann
Robert Mader
Robin Candau
Rudolf Polzer
Sadie Powell
Saijin-Naib
Sam Day
Sam Nystrom
Santurysim
Sascha Brawer
Sean E. Russell
Sean McAvoy
Sebastian Meyer
Sergiy Stupar
Sertonix
Simon Frankenberger
Simon Rupf
Simon Zeni
Siva Mahadevan
Sodface
Stanislav Kholmanskikh
Stefan Hansson
Stefan de Konink
Steffen Nurpmeso
Steve McMaster
Steven Guikal
Sumeet Jhand
Summpot
Sven Wick
Sylvain Prat
Sören Tempel
The one with the braid
Thomas Aldrian
Thomas Böhler
Thomas Deutsch
Thomas J Faughnan Jr
Thomas Kienlen
Thomas Liske
Timo Teräs
Timothy Legge
Tom Lebreux
Tom Wieczorek
Tuan Anh Tran
VehementHam
Vladimir Vitkov
Will Sinatra
William Desportes
William Wilhelm
Willow Barraco
Yann Vigara
Yao Zi
Zach DeCook
Zoey
adamthiede
alealexpro100
bin456789
blacksilver
chimo
crapStone
cristian_ci
dlatchx
donoban
duckl1ng
eletrotupi
famfo
fossdd
geek-at
gs250427
j.r
jahway603
jane400
juef
jvoisin
kamijo
knuxify
kpcyrd
lauren n. liberda
leso-kn
lucidiot
macmpi
michalszmidt
mini-bomba
mio
nezu
nibon7
odrling
omni
ovf
prspkt
psykose
ptrcnull
qaqland
rdbo
rubicon
sewn
shum
sodface
stepech
steve
streaksu
strophy
tetsumaki
timothysteward-wk
u8l
user
wesley van tilburg
xrs
znley
Štěpán Pechman
李通洲

ALPINE 3.19.1 RELEASED
We are pleased to announce the release of Alpine Linux 3.19.1, a maintenance release of the 3.19 series. This release includes various bug fixes and security updates, including security fixes for OpenSSL:

CVE-2023-6129
CVE-2023-6237
CVE-2024-0727
The full lists of changes can be found in the git log.

GIT SHORTLOG

Andy Postnikov (41):
      main/libavif: enable check on s390x
      community/composer: upgrade to 2.6.6
      community/php81-pecl-xdebug: upgrade to 3.3.1
      community/php82-pecl-xdebug: upgrade to 3.3.1
      community/php83-pecl-xdebug: upgrade to 3.3.1
      community/php83: exclude zend_test from binaries
      community/php82: exclude zend_test from binaries
      community/php81: exclude zend_test from binaries
      community/php83-pecl-imagick: new aport
      community/php81-pecl-ds: upgrade to 1.5.0
      community/php82-pecl-ds: upgrade to 1.5.0
      community/php83-pecl-ds: upgrade to 1.5.0
      community/php81: upgrade to 8.1.27
      community/php82: upgrade to 8.2.14
      community/php83: upgrade to 8.3.1
      community/php83-pecl-mongodb: upgrade to 1.17.2
      community/php82-pecl-mongodb: upgrade to 1.17.2
      community/php81-pecl-mongodb: upgrade to 1.17.2
      community/php81-pecl-event: upgrade to 3.1.0
      community/php82-pecl-event: upgrade to 3.1.0
      community/php83-pecl-event: upgrade to 3.1.0
      community/php81-pecl-event: upgrade to 3.1.1
      community/php82-pecl-event: upgrade to 3.1.1
      community/php83-pecl-event: upgrade to 3.1.1
      community/php81-pecl-timezonedb: upgrade to 2023.4
      community/php82-pecl-timezonedb: upgrade to 2023.4
      community/phpldapadmin: upgrade to 1.2.6.7
      community/php81-pecl-zstd: upgrade to 0.13.2
      community/php82-pecl-zstd: upgrade to 0.13.2
      community/php83-pecl-zstd: upgrade to 0.13.2
      community/php82: upgrade to 8.2.15
      community/php83: upgrade to 8.3.2
      community/php81-pecl-decimal: upgrade to 1.5.0 and modernize
      community/php82-pecl-decimal: upgrade to 1.5.0
      community/php81-pecl-amqp: upgrade to 2.1.2
      community/php82-pecl-amqp: upgrade to 2.1.2
      community/php83-pecl-amqp: upgrade to 2.1.2
      community/php81-pecl-event: upgrade to 3.1.2
      community/php82-pecl-event: upgrade to 3.1.2
      community/php83-pecl-event: upgrade to 3.1.2
      community/pipx: upgrade to 1.4.3

Antoine Martin (5):
      community/git-annex: upgrade to 10.20231227
      community/dotnet7-build: upgrade to 7.0.115
      community/dotnet7-runtime: upgrade to 7.0.15
      community/dotnet6-build: upgrade to 6.0.126
      community/dotnet6-runtime: upgrade to 6.0.26

Bart Ribbers (2):
      community/kde-applications: upgrade to 23.08.4
      community/plasma*: upgrade to 5.27.10

Celeste (58):
      main/glib: upgrade to 2.78.3
      community/npm: upgrade to 10.2.5
      main/nodejs: rebuild against ada 2.7.4
      main/jq: security upgrade to 1.7.1
      community/opensc: security upgrade to 0.24.0
      community/transmission: upgrade to 4.0.5
      main/squid: upgrade to 6.6
      community/libvterm: upgrade to 0.3.3
      community/rqlite: upgrade to 8.12.0
      main/putty: security upgrade to 0.80
      community/erlang: security upgrade to 26.2.1
      community/cloudi: rebuild against erlang 26.2.1
      community/elixir: rebuild against erlang 26.2.1
      community/eturnal: rebuild against erlang 26.2.1
      community/mongooseim: upgrade to 6.2.0
      community/filezilla: security upgrade to 3.66.4
      community/pijul: upgrade to 1.0.0_beta8
      community/gitea: security upgrade to 1.21.3
      community/guacamole-server: upgrade to 1.5.4
      community/jql: upgrade to 7.1.2
      community/git-lfs: upgrade to 3.4.1
      community/conmon: upgrade to 2.1.10
      community/exim: security upgrade to 4.97.1
      community/xerces-c: security upgrade to 3.2.5
      community/postgis: upgrade to 3.4.1
      community/py3-jwcrypto: security upgrade to 1.5.1
      community/wayshot: upgrade to 1.3.1
      community/cargo-make: upgrade to 0.37.5
      community/swc: upgrade to 1.3.102
      community/irust: upgrade to 1.71.19
      main/knot: upgrade to 3.3.3
      community/java-netty-transport-native: upgrade to 4.1.104
      main/redis: security upgrade to 7.2.4
      community/zbar: security upgrade to 0.23.93
      community/zlib-ng: upgrade to 2.1.6
      main/nodejs: upgrade to 20.11.0
      community/nebula: bump golang.org/x/crypto to patch CVE-2023-48795
      community/gnome-control-center: upgrade to 45.2
      community/snapshot: upgrade to 45.2
      community/gnome-settings-daemon: upgrade to 45.1
      community/deja-dup: upgrade to 45.2
      main/vala: upgrade to 0.56.14
      main/libsecret: upgrade to 0.21.2
      community/libshumate: upgrade to 1.1.2
      community/nautilus: upgrade to 45.2.1
      community/folks: upgrade to 0.15.7
      community/warp: upgrade to 0.6.2
      community/livi: upgrade to 0.0.5
      community/loupe: upgrade to 45.3
      community/librsvg: upgrade to 2.57.1
      community/vte3: upgrade to 0.74.2
      community/gitea: security upgrade to 1.21.4
      community/py3-sqlalchemy: upgrade to 2.0.25
      community/gjs: upgrade to 1.78.3
      community/livi: upgrade to 0.0.6
      main/glib: upgrade to 2.78.4
      main/knot: upgrade to 3.3.4
      community/py3-pillow: upgrade to 10.2.0

David Heidelberg (2):
      main/mesa: revert rusticl for freedreno
      main/mesa: upgrade to 23.3.1

Dhruvin Gandhi (2):
      community/hledger: upgrade to 1.32.2
      community/hledger-iadd: upgrade to 1.3.20

Fiona Klute (1):
      community/firefox-esr: security upgrade to 115.6.0

Henrik Riomar (1):
      community/nats-server: upgrade to 2.10.7

Hoang Nguyen (3):
      community/pulumi-language-java: upgrade to 0.9.9
      community/pulumi-language-yaml: upgrade to 1.4.5
      community/ntpsec: upgrade to 1.2.3

Holger Jaekel (2):
      community/gdal: upgrade to 3.8.2
      community/gdal: upgrade to 3.8.3

J0WI (16):
      community/powershell: security upgrade to 7.3.10
      main/squid: update secfixes
      community/cosign: security upgrade to 2.2.1
      main/asterisk: security upgrade to 20.5.1
      community/libsass: security upgrade to 3.6.6
      community/thunderbird: security upgrade to 115.6.0
      main/tzdata: upgrade to 2023d
      main/openssl: patch CVE-2023-6129
      main/openssl: patch CVE-2023-6237
      main/gnutls: security upgrade to 3.8.3
      community/cacti: security upgrade to 1.2.26
      main/mariadb: security upgrade to 10.11.6
      main/coreutils: patch CVE-2024-0684
      main/postfix: security upgrade to 3.8.5
      main/openssl: patch CVE-2024-0727
      community/py3-pillow: update secfixes

Jake Buchholz Göktürk (3):
      main/tiny-cloud: upgrade to 3.0.5
      main/tiny-cloud: cleanup APKBUILD
      main/tiny-cloud: upgrade to 3.0.7

Jakub Jirutka (5):
      community/keycloak-config-cli: upgrade to 5.10.0
      main/ruby: build with yjit
      community/alpine-make-vm-image: upgrade to 0.13.0
      community/kitty: fix wrong depends in -terminfo and -kitten subpkgs
      main/nftables: don't use nexthdr to match icmpv6

Jonathan Schleifer (2):
      [3.19] community/objfw: upgrade to 1.0.6
      [3.19] community/objfw: upgrade to 1.0.8

Kaarle Ritvanen (1):
      main/awall: upgrade to 1.12.3

Kevin Daudt (4):
      community/zabbix: upgrade to 6.4.10
      community/ffmpeg: security upgrade to 6.1
      community/vde2: rebuild against wolfssl-5.6.6
      main/gross: upgrade to 1.0.4

Krassy Boykinov (38):
      community/py3-gst: upgrade to 1.22.8
      main/gstreamer: upgrade to 1.22.8
      main/gst-plugins-base: upgrade to 1.22.8
      community/gst-plugins-good: upgrade to 1.22.8
      community/gst-plugins-bad: security upgrade to 1.22.8
      community/gst-plugins-ugly: upgrade to 1.22.8
      community/gst-libav: upgrade to 1.22.8
      testing/gst-rtsp-server: upgrade to 1.22.8
      community/gst-vaapi: upgrade to 1.22.8
      community/gst-editing-services: upgrade to 1.22.8
      main/libde265: security upgrade to 1.0.15
      community/mozjs115: security upgrade to 115.6.0
      community/thunderbird: upgrade to 115.6.1
      main/cjson: security upgrade to 1.7.17
      main/at-spi2-core: upgrade to 2.50.1
      community/libheif: security upgrade to 1.17.6
      community/imagemagick: upgrade to 7.1.1.26
      community/epiphany: upgrade to 45.2
      community/gjs: upgrade to 1.78.2
      community/mutter: upgrade to 45.3
      community/gnome-shell: upgrade to 45.3
      community/gnome-maps: upgrade to 45.3
      community/libadwaita: upgrade to 1.4.2
      community/libdex: upgrade to 0.4.3
      community/libpeas2: upgrade to 2.0.1
      community/libpanel: upgrade to 1.4.1
      community/evolution-data-server: upgrade to 3.50.3
      community/evolution: upgrade to 3.50.3
      community/evolution-ews: upgrade to 3.50.3
      community/ffmpeg: upgrade to 6.1.1
      main/zlib: upgrade to 1.3.1
      community/minizip: upgrade to 1.3.1
      main/c-ares: patch out dns sanity check
      community/thunderbird: security upgrade to 115.7.0
      community/mozjs115: security upgrade to 115.7.0
      community/firefox-esr: security upgrade to 115.7.0
      community/py3-img2pdf: upgrade to 0.5.1
      community/openexr: upgrade to 3.1.11

Leon Marz (1):
      community/blender: disable osl

Leonardo Arena (5):
      community/nextcloud: upgrade to 27.1.5
      community/lxd: add depend nftables
      community/lxd: build lxd-migrate tool
      community/lxd: allow running VMs
      community/lxd: fix QEMU features check

Magnus Sandin (1):
      community/clipboard: upgrade to 0.9.0

Michał Polański (4):
      community/caddy: upgrade to 2.7.6
      community/wlroots: upgrade to 0.17.1
      community/podman: upgrade to 4.8.3
      community/borgmatic: upgrade to 1.8.7

Milan P. Stanić (9):
      main/haproxy: upgrade to 2.8.5
      community/linux-edge: upgrade to 6.6.7
      community/xorg-server: security upgrade to 21.1.10
      community/linux-edge: upgrade to 6.6.8
      main/postfix: bugfix upgrade to 3.8.4
      community/linux-edge: upgrade to 6.6.9
      community/linux-edge: upgrade to 6.7.0
      community/xorg-server: security upgrade to 21.1.11
      community/xwayland: security upgrade to 23.2.4

Mogens Jensen (1):
      community/rxvt-unicode: add string-print.patch

Natanael Copa (99):
      main/linux-lts: upgrade to 6.6.5
      community/jool-modules-lts: rebuild against kernel 6.6.5-r0
      community/rtl8821ce-lts: rebuild against kernel 6.6.5-r0
      community/rtpengine-lts: rebuild against kernel 6.6.5-r0
      community/virtio_vmmci-lts: rebuild against kernel 6.6.5-r0
      community/vmm_clock-lts: rebuild against kernel 6.6.5-r0
      main/xtables-addons-lts: rebuild against kernel 6.6.5-r0
      main/zfs-lts: rebuild against kernel 6.6.5-r0
      main/linux-lts: upgrade to 6.6.6
      community/jool-modules-lts: rebuild against kernel 6.6.6-r0
      community/rtl8821ce-lts: rebuild against kernel 6.6.6-r0
      community/rtpengine-lts: rebuild against kernel 6.6.6-r0
      community/virtio_vmmci-lts: rebuild against kernel 6.6.6-r0
      community/vmm_clock-lts: rebuild against kernel 6.6.6-r0
      main/xtables-addons-lts: rebuild against kernel 6.6.6-r0
      main/zfs-lts: rebuild against kernel 6.6.6-r0
      main/linux-lts: upgrade to 6.6.7
      community/jool-modules-lts: rebuild against kernel 6.6.7-r0
      community/rtl8821ce-lts: rebuild against kernel 6.6.7-r0
      community/rtpengine-lts: rebuild against kernel 6.6.7-r0
      community/virtio_vmmci-lts: rebuild against kernel 6.6.7-r0
      community/vmm_clock-lts: rebuild against kernel 6.6.7-r0
      main/xtables-addons-lts: rebuild against kernel 6.6.7-r0
      main/zfs-lts: rebuild against kernel 6.6.7-r0
      community/ffmpeg: enable libharfbuzz
      main/devhelp: remove duplicate
      main/freeswitch: security upgrade to 1.10.10
      main/iptables: fix init.d to work with nft backend
      main/iptables: only create netns at start
      main/iptables: various init.d fixes and improvements
      scripts/mkimg.arm.sh: improve description for Pi images
      main/linux-lts: upgrade to 6.6.8
      community/jool-modules-lts: rebuild against kernel 6.6.8-r0
      community/rtl8821ce-lts: rebuild against kernel 6.6.8-r0
      community/rtpengine-lts: rebuild against kernel 6.6.8-r0
      community/virtio_vmmci-lts: rebuild against kernel 6.6.8-r0
      community/vmm_clock-lts: rebuild against kernel 6.6.8-r0
      main/xtables-addons-lts: rebuild against kernel 6.6.8-r0
      main/zfs-lts: rebuild against kernel 6.6.8-r0
      main/linux-lts: upgrade to 6.6.9
      community/jool-modules-lts: rebuild against kernel 6.6.9-r0
      community/rtl8821ce-lts: rebuild against kernel 6.6.9-r0
      community/rtpengine-lts: rebuild against kernel 6.6.9-r0
      community/virtio_vmmci-lts: rebuild against kernel 6.6.9-r0
      community/vmm_clock-lts: rebuild against kernel 6.6.9-r0
      main/xtables-addons-lts: rebuild against kernel 6.6.9-r0
      main/zfs-lts: rebuild against kernel 6.6.9-r0
      main/linux-lts: upgrade to 6.6.10
      community/jool-modules-lts: rebuild against kernel 6.6.10-r0
      community/rtl8821ce-lts: rebuild against kernel 6.6.10-r0
      community/rtpengine-lts: rebuild against kernel 6.6.10-r0
      community/virtio_vmmci-lts: rebuild against kernel 6.6.10-r0
      community/vmm_clock-lts: rebuild against kernel 6.6.10-r0
      main/xtables-addons-lts: rebuild against kernel 6.6.10-r0
      main/zfs-lts: rebuild against kernel 6.6.10-r0
      community/qemu: upgrade to 8.1.4
      main/linux-lts: upgrade to 6.6.11
      community/jool-modules-lts: rebuild against kernel 6.6.11-r0
      community/rtl8821ce-lts: rebuild against kernel 6.6.11-r0
      community/rtpengine-lts: rebuild against kernel 6.6.11-r0
      community/virtio_vmmci-lts: rebuild against kernel 6.6.11-r0
      community/vmm_clock-lts: rebuild against kernel 6.6.11-r0
      main/xtables-addons-lts: rebuild against kernel 6.6.11-r0
      main/zfs-lts: rebuild against kernel 6.6.11-r0
      main/openrc: backport fix for cgroupv2 and docker
      main/linux-lts: upgrade to 6.6.12
      community/jool-modules-lts: rebuild against kernel 6.6.12-r0
      community/rtl8821ce-lts: rebuild against kernel 6.6.12-r0
      community/rtpengine-lts: rebuild against kernel 6.6.12-r0
      community/virtio_vmmci-lts: rebuild against kernel 6.6.12-r0
      community/vmm_clock-lts: rebuild against kernel 6.6.12-r0
      main/xtables-addons-lts: rebuild against kernel 6.6.12-r0
      main/zfs-lts: rebuild against kernel 6.6.12-r0
      main/linux-rpi: upgrade to 6.6.12
      community/jool-modules-rpi: rebuild against kernel 6.6.12-r0
      main/zfs-rpi: rebuild against kernel 6.6.12-r0
      main/linux-lts: upgrade to 6.6.13 & fix CVE-2023-46838 / XSA-448
      main/xtables-addons-lts: rebuild against kernel 6.6.13-r0
      main/zfs-lts: rebuild against kernel 6.6.13-r0
      community/jool-modules-lts: rebuild against kernel 6.6.13-r0
      community/rtl8821ce-lts: rebuild against kernel 6.6.13-r0
      community/rtpengine-lts: rebuild against kernel 6.6.13-r0
      community/virtio_vmmci-lts: rebuild against kernel 6.6.13-r0
      community/vmm_clock-lts: rebuild against kernel 6.6.13-r0
      main/linux-lts: upgrade to 6.6.14
      community/jool-modules-lts: rebuild against kernel 6.6.14-r0
      community/rtl8821ce-lts: rebuild against kernel 6.6.14-r0
      community/rtpengine-lts: rebuild against kernel 6.6.14-r0
      community/virtio_vmmci-lts: rebuild against kernel 6.6.14-r0
      community/vmm_clock-lts: rebuild against kernel 6.6.14-r0
      main/xtables-addons-lts: rebuild against kernel 6.6.14-r0
      main/zfs-lts: rebuild against kernel 6.6.14-r0
      main/linux-rpi: upgrade to 6.6.14
      community/jool-modules-rpi: rebuild against kernel 6.6.14-r0
      main/zfs-rpi: rebuild against kernel 6.6.14-r0
      main/mkinitfs: upgrade to 3.9.1
      main/alpine-conf: upgrade to 3.17.2
      main/raspberrypi-bootloader: upgrade to 20240122
      ===== release 3.19.1 =====

Sertonix (2):
      main/ifupdown-ng: remove -openrc subpackage
      main/openrc: remove ifupdown-ng-openrc

Simon Frankenberger (6):
      community/java-libsignal-client: move from testing
      community/signal-cli: move from testing
      community/proftpd: upgrade to 1.3.8b
      community/openjdk11: upgrade to 11.0.22
      community/openjdk17: upgrade to 17.0.10
      community/openjdk21: upgrade to 21.0.2

Sören Tempel (1):
      community/go: upgrade to 1.21.6

Thomas Liske (4):
      community/ifstate: upgrade to 1.11.4
      community/bird-lg-go: upgrade to 1.3.5
      community/ifstate: upgrade to 1.11.5
      community/ifstate: upgrade to 1.11.6

Timothy Legge (1):
      community/perl-spreadsheet-parseexcel: upgrade to 0.66

Will Sinatra (1):
      community/doctl: security upgrade to 1.102.0

aptalca (1):
      main/c-ares: upgrade to 1.24.0

bin456789 (3):
      main/linux-lts: enable hyper-v drivers for aarch64
      main/linux-lts: enable CONFIG_HYPERV_VSOCKETS for x86 and x86_64
      main/linux-lts: enable mlx4_en, mlx5_en to use SR-IOV VFs in VM

jane400 (1):
      community/gnome-text-editor: upgrade to 45.2

lauren n. liberda (7):
      community/chromium: backport from edge
      community/chromium: security upgrade to 120.0.6099.109
      community/chromium: security upgrade to 120.0.6099.129
      community/chromium: security upgrade to 120.0.6099.199
      community/chromium: security upgrade to 120.0.6099.216
      community/chromium: security upgrade to 120.0.6099.224
      community/chromium: upgrade to 121.0.6167.85

omni (29):
      community/tor: security upgrade to 0.4.8.10
      main/asterisk: rebuild
      community/judo: move examples to -doc subpackage
      community/py3-psycopg: upgrade to 3.1.15
      main/xen: add mitigations for XSA-447 (armv7)
      community/unrealircd: security upgrade to 6.1.4
      community/py3-psycopg: check for typing_extensions
      community/py3-psycopg: update typing_exteensions patch
      main/openssh: security upgrade to 9.6p1
      community/libssh: security upgrade to 0.10.6
      community/py3-paramiko: security upgrade to 3.4.0
      main/dropbear: add mitigations for CVE-2023-48795
      community/qt6-qtwebengine: chromium security upgrade
      community/py3-asyncssh: security upgrade to 2.14.2
      main/libssh2: add mitigations for CVE-2023-48795
      community/py3-asyncssh: add secfixes for CVE-2023-48795
      community/ssh-audit: upgrade to 3.1.0
      community/tinyssh: add mitigations for CVE-2023-48795
      community/podman-tui: security upgrade to 0.15.0
      community/buildah: add mitigations for CVE-2023-48795
      community/podman: add mitigations for CVE-2023-48795
      community/wolfssl: security upgrade to 5.6.6
      main/asterisk: upgrade to 20.5.2
      community/qt6-qtwebengine: chromium security upgrade
      community/qt5-qtwebengine: chromium security upgrade
      community/qt6-qtwebengine: chromium security upgrade
      community/qt6-qtwebengine: chromium security upgrade
      community/bzrtp: upgrade to 5.2.112
      community/qt5-qtwebengine: chromium security upgrade

ptrcnull (9):
      community/gitlab-runner: upgrade to 16.6.1
      main/rrdtool: fix segfault on start
      community/thunderbird: upgrade to 115.5.2
      community/qt5-qtbase: disable sse3 on x86
      community/gvfs: upgrade to 1.52.1
      community/firefox: upgrade to 122.0
      community/firefox: disable Widevine CDM support
      community/firefox: enable crash reporting
      main/nss: upgrade to 3.97

streaksu (1):
      community/limine: upgrade to 5.20231207.1

ALPINE 3.16.9, 3.17.7 AND 3.18.6 RELEASED
The Alpine Linux project is pleased to announce the immediate availability of new stable releases:

3.16.9
3.17.7
3.18.6
Those releases include security fixes for openssl:

CVE-2023-6129
CVE-2023-6237
CVE-2024-0727


ALPINE LINUX 3.19.0 RELEASED
We are pleased to announce the release of Alpine Linux 3.19.0, the first in the v3.19 stable series.

HIGHLIGHTS
Linux kernel 6.6
GCC 13.2
Perl 5.38
LLVM 17
Xen 4.18
PostgreSQL 16
Node.js (lts) 20.10
Ceph 18.2
GNOME 45
Go 1.21
KDE Applications 23.08 / KDE Frameworks 5.112
OpenJDK 21
PHP 8.3
Rust 1.72
SIGNIFICANT CHANGES
Support for Raspberry Pi 5 was added.

UPGRADE NOTES
As always, make sure to use apk upgrade --available when switching between major versions.

openrc has removed the deprecated /sbin/rc binary. Make sure your /etc/inittab uses /sbin/openrc.
iptables-nft is now the default iptables backend.
EFI_ZBOOT was enabled for aarch64 kernels. This change requires grub to be reinstalled with grub-install --bootloader-id=alpine --no-nvram --efi-directory=/boot (or /boot/efi)
linux-rpi4 and linux-rpi2 kernels have been replaced by a single linux-rpi
yggdrasil was upgraded to 0.5 and the new routing scheme is incompatible with previous versions.
Python’s package directory is now marked as externally managed, which means that pip can no longer install to system directory which is managed by apk. Users may use pipx instead.
CHANGES
The full list of changes can be found in the wiki, git log and bug tracker.

CREDITS
Thanks to everyone sending patches, bug reports, new and updated aports, and to everyone helping with writing documentation, maintaining the infrastructure, or contributing in any other way!

Thanks to GIGABYTE, Linode, Fastly, IBM, Equinix Metal, vpsFree and ungleich for providing us with hardware and hosting.

APORTS COMMIT CONTRIBUTORS
6543
Adam Bruce
Adam Jensen
Adam Saponara
Adam Thiede
Ado
Adrián Arroyo Calle
Affe Null
Aiden Grossman
Aleks Bunin
Alex
Alex Denes
Alex McGrath
Alex Sivchev
Alexander Birkner
Alexey Minnekhanov
Alexey Yerin
Alistair Francis
Alois Klink
Andrei Jiroh Halili
Andrei Zavada
Andrej Kolchin
Andres Almiray
André Klitzing
Andy Hawkins
Andy Li
Andy Postnikov
Anjandev Momi
Anon Anon
Antoine Martin
Anton Bambura
Antoni Aloy Torrens
Ariadne Conill
Arnav Singh
Assaf Inbal
Aydin Mercan
Ayush Agarwal
Bader Zaidan
Bart Ribbers
Ben Westover
Benoit Masson
Bernd Rothert
Bobby Hamblin
Bryant Mairs
Bryce Vandegrift
BugFest
Caleb Connolly
Carlo Landmeter
Celeste
Chaiwat Suttipongsakul
Clayton Craft
Coco Liliace
Conrad Hoffmann
Cowington Post
Craig Comstock
Curt Tilmes
Damian Kurek
Daniel Fancsali
Daniel Néri
Dave Henderson
David Demelier
David Florness
David Heidelberg
Dekedro
Dennis Przytarski
Dermot Bradley
Dhruvin Gandhi
Dmitry Zakharchenko
Dominika Liberda
Dominique Martinet
Drew DeVault
Duncan Bellamy
Dylan Van Assche
Díaz Urbaneja Víctor Diego Alejandro (Sodomon)
Edd Salkield
Elly Fong-Jones
Eloi Torrents
Evan Johsnton
Even Rouault
Fabricio Silva
Faustin Lammler
Fiona Klute
Firas Khalil Khana
Florian Schwarzmeier
FollieHiyuki
Forza
Francesco Colista
Francesco Palumbo
Frank Oltmanns
Fxzx mic
Gabor Csardi
Gabriel Arakaki Giovanini
Galen Abell
Gavin Henry
Gennady Feldman
GitHub Action
Glenn Strauss
Grigory Kirillov
Guilherme Macedo
Guillaume Quintard
Guy Godfroy
Gábor Csárdi
Haelwenn (lanodan) Monnier
Hakan Erduman
Henrik Riomar
Hoang Nguyen
Holger Jaekel
Hristiyan Ivanov
Hugo Osvaldo Barrera
Hugo Rodrigues
Hugo Wang
Hygna
IP2Location
Iskren Chernev
Ivan Popovych
Iztok Fister Jr
Iztok Fister Jr.
J0WI
Jake Buchholz Göktürk
Jakob Hauser
Jakob Meier
Jakub Jirutka
Jakub Panek
Jan Samek
Janik Besendorf
Jason Swank
Jean-Christophe Amiel
Jeff Dickey
Jingyun Hua
Jiri Kastner
Jo Coscia
John Anthony
John Gebbie
John Vogel
Jonas
Jonathan Schleifer
Jordan Christiansen
Josef Vybíhal
Joshua Murphy
Julie Koubova
JuniorJPDJ
Justin
Justinas Grigas
KAA the Wise
Kaarle Ritvanen
Kaspar Schleiser
Kevin Daudt
Khem Raj
Klaus Frank
Klemens Nanni
Konstantin Kulikov
Krassy Boykinov
Krystian Chachuła
Laszlo Gombos
Lauren N. Liberda
Laurent Bercot
Lennart Jablonka
Leon Marz
Leon ROUX
Leonardo Arena
Lindsay Zhou
Luca Weiss
Lucidiot
M Hickford
Maarten van Gompel
Magnus Sandin
Marian Buschsieweke
Mark Hills
Markus Göllnitz
Martijn Braam
Matthew T Hoare
Matthias Ahouansou
Mauricio Sandt
Michael M
Michael Pirogov
Michael Truog
Michal Jirku
Michal Tvrznik
Michał Adamski
Michał Polański
Michał Szmidt
Mike Crute
Milan P. Stanić
Miles Alan
Mogens Jensen
Nash Kaminski
Natanael Copa
Nathan Rennie-Waldock
Nero
Newbyte
Nia Espera
Nic Boet
Nicolas Lorin
Niklas Meyer
Niko
Nulo
Oleg Titov
Oliver Kuckertz
Oliver Smith
Oliver Wilkes
Olliver Schinagl
Orhun Parmaksız
Pablo Correa Gómez
Paolo Barbolini
Papiris
Paul Spooren
Pedro Lucas Porcellis
Peter Shkenev
Peter van Dijk
Petr Hodina
Philipp Arras
Phillip Jaenke
Piraty
Prokop Randacek
QC8086
R4SAS
Rabindra Dhakal
Ralf Rachinger
Raymond Page
Renê de Souza Pinto
Ricardo F
Rob Blanckaert
Rosie K Languet
Rudolf Polzer
Ruven
SSD
Saijin-Naib
Sam Edwards
Sam Nystrom
Sando
Sascha Brawer
Sean McAvoy
Sergio Talens-Oliag
Sergiy Stupar
Sertonix
Sicelo A. Mhlongo
Simon Frankenberger
Simon Rupf
Simon Zeni
Siva Mahadevan
Sodface
Stanislav Kholmanskikh
Stefan Hansson
Steve McMaster
Steven Brudenell
Steven Guikal
Steven Honson
Steven Vanden Branden
Stuart Cardall
Sylvain Prat
Síle Ekaterin Liszka
Sören Tempel
Ted Trask
Thomas Aldrian
Thomas Böhler
Thomas Deutsch
Thomas Faughnan
Thomas J Faughnan Jr
Thomas Kienlen
Thomas Liske
Tim Magee
Timo Teräs
Timothy Legge
Tom Lebreux
Tom Wieczorek
Umar Getagazov
Usia Bechtle
Val V
Valery Ushakov
Veikka Valtteri Kallinen
Viet Pham
Vlad Glagolev
Vladimir Vitkov
Wesley van Tilburg
Weston Steimel
Will Sinatra
William Desportes
William Walker
Willow Barraco
Yang Xiwen
Yann Vigara
Yingbai He
Zach DeCook
Zachary Andrews
Zsolt Vadasz
adamthiede
alealexpro100
aptalca
bin456789
crapStone
donoban
duckl1ng
elruwen
fanquake
guddaff
hitechshell
j.r
jahway603
jane400
john3dc
jvoisin
knuxify
kpcyrd
lauren n. liberda
lazywalker
leso-kn
lgehr
linear cannon
llightcb
macmpi
mbrowny
messense
michalszmidt
mio
nezu
nibon7
notfound405
omni
ovf
papiris
prspkt
psykose
ptrcnull
qaqland
rubicon
sando38
sodface
streaksu
sudotac
svrnm
takumin
techknowlogick
tetsumaki
tiotags
w
wener
zamfofex

ALPINE 3.15.11, 3.16.8, 3.17.6 AND 3.18.5 RELEASED
The Alpine Linux project is pleased to announce the immediate availability of new stable releases:

3.15.11
3.16.8
3.17.6
3.18.5
Those releases include security fixes for openssl:

CVE-2023-5678
CVE-2023-5363

ALPINE 3.18.4 RELEASED
We are pleased to announce the release of Alpine Linux 3.18.4, a maintenance release of the 3.18 series. This release includes various bug fixes and security updates.

The full lists of changes can be found in the git log.

GIT SHORTLOG
Alex McGrath (1):
      community/transmission: upgrade to 4.0.4

Andy Postnikov (9):
      community/php82-pecl-couchbase: upgrade to 4.1.5
      community/php81-pecl-couchbase: upgrade to 4.1.5
      community/php81-pecl-mailparse: upgrade to 3.1.6
      main/nodejs: security upgrade to 18.17.1
      community/php82: upgrade to 8.2.9
      community/php82: upgrade to 8.2.10
      community/php81: upgrade to 8.1.23
      community/php81-pecl-redis: upgrade to 6.0.0
      community/php82-pecl-redis: upgrade to 6.0.0

Antoine Martin (9):
      community/dotnet7-build: upgrade to 7.0.110
      community/dotnet7-runtime: upgrade to 7.0.10
      community/dotnet6-build: upgrade to 6.0.121
      community/dotnet6-runtime: upgrade to 6.0.21
      community/dotnet6-build: upgrade to 6.0.122
      community/dotnet6-runtime: upgrade to 6.0.22
      community/git-annex: upgrade to 10.20230828
      community/dotnet7-build: security upgrade to 7.0.111
      community/dotnet7-runtime: security upgrade to 7.0.11

Bart Ribbers (1):
      community/koko: make it easier to update geodata

Celeste (27):
      main/mosquitto: upgrade to 2.0.16
      main/mosquitto: upgrade to 2.0.17
      community/neo4j: upgrade to 4.4.25
      community/java-netty-transport-native: upgrade to 4.1.97
      community/vnstat: upgrade to 2.11
      community/python3-tkinter: upgrade to 3.11.5
      main/python3: security upgrade to 3.11.5
      community/xrdp: security upgrade to 0.9.23
      community/borgbackup: security upgrade to 1.2.6
      community/open-vm-tools: security upgrade to 12.3.0
      community/py3-django: security upgrade to 4.2.5
      main/mariadb: upgrade to 10.11.5
      main/redis: security upgrade to 7.0.13
      community/neovim: upgrade to 0.9.2
      community/py3-openssl: upgrade to 23.2.0
      community/ruby-pkg-config: upgrade to 1.5.5
      community/ruby-timecop: upgrade to 0.9.8
      community/netatalk: security upgrade to 3.1.17
      main/cups: security upgrade to 2.4.7
      main/curl: security upgrade to 8.3.0
      community/minio: upgrade to 0.20230920.224955
      main/bind: security upgrade to 9.18.19
      community/stunnel: upgrade to 5.71
      community/neo4j: upgrade to 4.4.26
      community/keepassxc: upgrade to 2.7.6
      community/synapse: security upgrade to 1.93.0
      community/xrdp: security upgrade to 0.9.23.1

Dhruvin Gandhi (1):
      community/hledger-interest: upgrade to 1.6.6

Duncan Bellamy (3):
      main/mariadb: add fmt10 patches
      community/ceph16: upgrade to 16.2.14
      community/py3-cryptography: security upgrade to 41.0.3 for CVE-2023-38325

Elly Fong-Jones (1):
      community/chromium: roll 3.18-stable to 117.0.5938.62

Francesco Colista (7):
      community/py3-sentry-sdk: upgrade to 1.24.0
      community/perl-business-isbn-data: upgrade to 20230516.001
      main/sofia-sip: bump pkgrel
      community/lua-resty-lock: backport from edge
      community/lua-resty-lock: added missing dep
      community/lua-resty-lock: bump pkgrel due to added depend
      community/lua-resty-lock: fix build due to luajit missing for ppc64 and riscv64

Henrik Riomar (3):
      main/intel-ucode: security upgrade to 20230808
      main/xen: security upgrade to 4.17.2
      community/nats-server: upgrade to 2.9.22

Hugo Osvaldo Barrera (1):
      community/linux-edge: set CONFIG_KEXEC=y

J0WI (5):
      community/firefox-esr: security upgrade to 115.1.0
      community/thunderbird: security upgrade to 115.1.0
      community/ntpsec: security upgrade to 1.2.2a
      main/procps-ng: security upgrade to 4.0.4
      community/wolfssl: upgrade to 5.6.3

Jake Buchholz Göktürk (1):
      main/tiny-cloud: [3.18] upgrade to 3.0.2

Jakub Jirutka (15):
      community/apk-deploy-tool: upgrade to 0.5.3
      main/postgresql15: security upgrade to 15.4
      main/postgresql14: security upgrade to 14.9
      community/postgresql13: security upgrade to 13.12
      community/postgresql12: security upgrade to 12.16
      community/qemu-openrc: upgrade to 0.11.1
      community/jetty-runner: use exec in jetty-runner script
      community/jetty-runner: init: allow to override $command
      community/jetty-runner: check server_{access,out}_log location
      community/jetty-runner: upgrade to 9.4.51.20230217
      community/jetty-runner: fix perms and backport rest of changes from edge
      community/jetty-runner: add $start_wait to init script
      main/one-context: upgrade to 0.8.0
      main/linux-lts: enable EFI_ZBOOT on aarch64
      community/alpine-make-vm-image: upgrade to 0.12.0

Jakub Panek (3):
      community/rust: security upgrade to 1.71.1, take ownership
      community/rust-analyzer: upgrade to 2023.08.28, takeover maintainership
      community/rust-analyzer: upgrade to 2023.09.18

Jiri Kastner (1):
      mariadb: re-enable partition plugin

Kaarle Ritvanen (1):
      community/py3-django-oscar: align with upstream

Kevin Daudt (5):
      community/docker-cli-buildx: backport host header patch to docker
      community/tea: fix checksum filename
      community/vault: security upgrade to 1.13.5
      community/nfpm: upgrade to 2.32.0
      community/qemu: upgrade to 8.0.5

Leonardo Arena (1):
      community/nextcloud: upgrade to 26.0.5

Michał Polański (2):
      community/py3-trove-classifiers: upgrade to 2023.9.19
      main/openssl: upgrade to 3.1.3

Milan P. Stanić (12):
      community/linux-edge: upgrade to 6.4.9
      main/haproxy: bugfix upgrade to 2.6.15
      community/linux-edge: upgrade to 6.4.10
      community/qemu: upgrade to 8.0.4
      community/linux-edge: upgrade to 6.4.12
      community/linux-edge: upgrade to 6.5.0
      main/postfix: bugfix upgrade to 3.8.2
      community/linux-edge: upgrade to 6.5.1
      community/linux-edge: upgrade to 6.5.2
      community/mutt: bugfix upgrade to 2.2.12
      community/linux-edge: upgrade to 6.5.3
      community/linux-edge: upgrade to 6.5.5

Natanael Copa (104):
      community/gitlab-runner: backport docker cli fix
      main/samba: add secfixes info
      main/samba: add secfixes comment
      main/linux-lts: upgrade to 6.1.44
      community/jool-modules-lts: rebuild against kernel 6.1.44-r0
      community/rtl8821ce-lts: rebuild against kernel 6.1.44-r0
      community/rtpengine-lts: rebuild against kernel 6.1.44-r0
      community/virtio_vmmci-lts: rebuild against kernel 6.1.44-r0
      community/vmm_clock-lts: rebuild against kernel 6.1.44-r0
      main/xtables-addons-lts: rebuild against kernel 6.1.44-r0
      main/zfs-lts: rebuild against kernel 6.1.44-r0
      main/linux-lts: upgrade to 6.1.45
      community/jool-modules-lts: rebuild against kernel 6.1.45-r0
      community/rtl8821ce-lts: rebuild against kernel 6.1.45-r0
      community/rtpengine-lts: rebuild against kernel 6.1.45-r0
      community/virtio_vmmci-lts: rebuild against kernel 6.1.45-r0
      community/vmm_clock-lts: rebuild against kernel 6.1.45-r0
      main/xtables-addons-lts: rebuild against kernel 6.1.45-r0
      main/zfs-lts: rebuild against kernel 6.1.45-r0
      main/linux-lts: fix x86 PAE and HIGHMEM
      main/linux-lts: upgrade to 6.1.46
      community/jool-modules-lts: rebuild against kernel 6.1.46-r0
      community/rtl8821ce-lts: rebuild against kernel 6.1.46-r0
      community/rtpengine-lts: rebuild against kernel 6.1.46-r0
      community/virtio_vmmci-lts: rebuild against kernel 6.1.46-r0
      community/vmm_clock-lts: rebuild against kernel 6.1.46-r0
      main/xtables-addons-lts: rebuild against kernel 6.1.46-r0
      main/zfs-lts: rebuild against kernel 6.1.46-r0
      main/linux-lts: use default log buffer size
      main/linux-lts: upgrade to 6.1.47
      community/jool-modules-lts: rebuild against kernel 6.1.47-r0
      community/rtl8821ce-lts: rebuild against kernel 6.1.47-r0
      community/rtpengine-lts: rebuild against kernel 6.1.47-r0
      community/virtio_vmmci-lts: rebuild against kernel 6.1.47-r0
      community/vmm_clock-lts: rebuild against kernel 6.1.47-r0
      main/xtables-addons-lts: rebuild against kernel 6.1.47-r0
      main/zfs-lts: rebuild against kernel 6.1.47-r0
      main/sofia-sip: backport of support for forking calls. See mr #50659
      main/linux-lts: upgrade to 6.1.49
      community/jool-modules-lts: rebuild against kernel 6.1.49-r0
      community/rtl8821ce-lts: rebuild against kernel 6.1.49-r0
      community/rtpengine-lts: rebuild against kernel 6.1.49-r0
      community/virtio_vmmci-lts: rebuild against kernel 6.1.49-r0
      community/vmm_clock-lts: rebuild against kernel 6.1.49-r0
      main/xtables-addons-lts: rebuild against kernel 6.1.49-r0
      main/zfs-lts: rebuild against kernel 6.1.49-r0
      community/thunderbird: upgrade to 115.1.1
      main/sofia-sip: actually add the patch
      main/linux-lts: upgrade to 6.1.50
      community/jool-modules-lts: rebuild against kernel 6.1.50-r0
      community/rtl8821ce-lts: rebuild against kernel 6.1.50-r0
      community/rtpengine-lts: rebuild against kernel 6.1.50-r0
      community/virtio_vmmci-lts: rebuild against kernel 6.1.50-r0
      community/vmm_clock-lts: rebuild against kernel 6.1.50-r0
      main/xtables-addons-lts: rebuild against kernel 6.1.50-r0
      main/zfs-lts: rebuild against kernel 6.1.50-r0
      main/linux-lts: upgrade to 6.1.51
      community/jool-modules-lts: rebuild against kernel 6.1.51-r0
      community/rtl8821ce-lts: rebuild against kernel 6.1.51-r0
      community/rtpengine-lts: rebuild against kernel 6.1.51-r0
      community/virtio_vmmci-lts: rebuild against kernel 6.1.51-r0
      community/vmm_clock-lts: rebuild against kernel 6.1.51-r0
      main/xtables-addons-lts: rebuild against kernel 6.1.51-r0
      main/zfs-lts: rebuild against kernel 6.1.51-r0
      main/linux-lts: upgrade to 6.1.52
      community/jool-modules-lts: rebuild against kernel 6.1.52-r0
      community/rtl8821ce-lts: rebuild against kernel 6.1.52-r0
      community/rtpengine-lts: rebuild against kernel 6.1.52-r0
      community/virtio_vmmci-lts: rebuild against kernel 6.1.52-r0
      community/vmm_clock-lts: rebuild against kernel 6.1.52-r0
      main/xtables-addons-lts: rebuild against kernel 6.1.52-r0
      main/zfs-lts: rebuild against kernel 6.1.52-r0
      Revert "main/linux-lts: enable EFI_ZBOOT on aarch64"
      main/linux-lts: upgrade to 6.1.53
      community/jool-modules-lts: rebuild against kernel 6.1.53-r0
      community/rtl8821ce-lts: rebuild against kernel 6.1.53-r0
      community/rtpengine-lts: rebuild against kernel 6.1.53-r0
      community/virtio_vmmci-lts: rebuild against kernel 6.1.53-r0
      community/vmm_clock-lts: rebuild against kernel 6.1.53-r0
      main/xtables-addons-lts: rebuild against kernel 6.1.53-r0
      main/zfs-lts: rebuild against kernel 6.1.53-r0
      main/libwebp: upgrade to 1.3.2
      community/lua-resty-session: upgrade to 3.10
      community/lua-bitop: fix with lua 5.2+ and run tests
      main/linux-lts: upgrade to 6.1.54
      community/jool-modules-lts: rebuild against kernel 6.1.54-r0
      community/rtl8821ce-lts: rebuild against kernel 6.1.54-r0
      community/rtpengine-lts: rebuild against kernel 6.1.54-r0
      community/virtio_vmmci-lts: rebuild against kernel 6.1.54-r0
      community/vmm_clock-lts: rebuild against kernel 6.1.54-r0
      main/xtables-addons-lts: rebuild against kernel 6.1.54-r0
      main/zfs-lts: rebuild against kernel 6.1.54-r0
      main/linux-lts: upgrade to 6.1.55
      community/jool-modules-lts: rebuild against kernel 6.1.55-r0
      community/rtl8821ce-lts: rebuild against kernel 6.1.55-r0
      community/rtpengine-lts: rebuild against kernel 6.1.55-r0
      community/virtio_vmmci-lts: rebuild against kernel 6.1.55-r0
      community/vmm_clock-lts: rebuild against kernel 6.1.55-r0
      main/xtables-addons-lts: rebuild against kernel 6.1.55-r0
      main/zfs-lts: rebuild against kernel 6.1.55-r0
      main/linux-rpi: upgrade to 6.1.55
      community/jool-modules-rpi: rebuild against kernel 6.1.55-r0
      main/zfs-rpi: rebuild against kernel 6.1.55-r0
      ===== release 3.18.4 =====

Oleg Titov (1):
      community/k3s: security upgrade to 1.27.5.1

Pablo Correa Gómez (1):
      community/gnome-console: upgrade to 44.4

Peter van Dijk (1):
      community/dnsdist: upgrade to 1.8.1

Sertonix (1):
      community/keepassxc: fix opening doc from gui

Simon Frankenberger (1):
      community/openjdk17: upgrade to 17.0.8

Simon Rupf (1):
      community/clamav: upgrade to 1.1.2

Siva Mahadevan (1):
      community/linux-edge: add initial support for pinebook pro

Steven Guikal (1):
      community/py3-flask: security upgrade to 2.2.5 (CVE-2023-30861)

Sören Tempel (3):
      community/go: upgrade to 1.20.8
      community/*: rebuild with Go 1.20.8
      main/busybox: update secfixes (CVE-2022-48174)

Zach DeCook (1):
      community/verovio: upgrade to 3.15.0 and fix py3-verovio subpackage

bin456789 (1):
      main/linux-lts: enable Google Virtual NIC (gVNIC) driver

jahway603 (1):
      community/nextcloud: upgrade to 26.0.7

jane400 (1):
      main/libwebp: patch CVE-2023-4863

lauren n. liberda (2):
      community/yt-dlp: mark CVE as resolved
      community/libvpx: hotfix for CVE-2023-5217

macmpi (4):
      community/raspberrypi-utils: upgrade to 0.20230809
      main/raspberrypi-bootloader: upgrade to 1.20230811
      community/raspberrypi-utils: upgrade to 0.20230919
      main/raspberrypi-bootloader: upgrade to 1.20230921

omni (16):
      community/qt5-qtwebengine: chromium security upgrade
      community/tor: upgrade to 0.4.8.4
      community/tor: disable a test also for x86_64
      community/tor: upgrade to 0.4.8.5
      community/qt5-qtwebengine: chromium security upgrade
      community/arti: upgrade to 1.1.8
      community/qt5-qtwebengine: chromium security upgrade
      main/libarchive: security upgrade to 3.7.2
      community/qt5-qtimageformats: patch CVE-2023-4863
      community/qt6-qtimageformats: patch CVE-2023-4863
      community/qt5-qtwebengine: chromium security upgrade
      community/tor: upgrade to 0.4.8.6
      main/xen: add mitigations for XSA-437 & XSA-438
      main/linux-lts: fix pkgrel
      community/tor: upgrade to 0.4.8.7
      main/xen: add mitigations for XSA-439

ptrcnull (5):
      community/telegraf: fix embedding version
      community/firefox: upgrade to 116.0.3
      community/tea: rebuild against go 1.20.7
      community/firefox: fix sqlite3 on ppc with clang
      community/kitty: disable check on ppc64le

streaksu (6):
      community/limine: upgrade to 4.20230811.0
      community/limine: take over maintainership
      community/limine: upgrade to 4.20230830.0
      community/limine: upgrade to 4.20230911.0
      community/limine: upgrade to 4.20230917.0
      community/limine: upgrade to 4.20230924.0

ALPINE 3.15.10, 3.16.7, 3.17.5 AND 3.18.3 RELEASED
The Alpine Linux project is pleased to announce the immediate availability of new stable releases:

3.15.10
3.16.7
3.17.5
3.18.3
Those releases include security fixes for openssl:

CVE-2023-2975
CVE-2023-3446
CVE-2023-3817

ALPINE 3.15.9, 3.16.6, 3.17.4 AND 3.18.2 RELEASED
The Alpine Linux project is pleased to announce the immediate availability of new stable releases:

3.15.9
3.16.6
3.17.4
3.18.2
Those releases include security fixes for openssl:

CVE-2023-1255
CVE-2023-2650

ALPINE LINUX 3.18.0 RELEASED
We are pleased to announce the release of Alpine Linux 3.18.0, the first in the v3.18 stable series.

HIGHLIGHTS
Linux kernel 6.1 – with signed kernel modules
musl libc 1.2.4 – now with TCP fallback in DNS resolver
Python 3.11
Ruby 3.2
Node.js (current) 20.1
GNOME 44
Go 1.20
KDE Plasma 5.27
Rust 1.69
Experimental support for unattended installs via tiny-cloud
SIGNIFICANT CHANGES
Kernel modules are now signed. Verified modules are not enforced by default, so 3rd party modules with akms still works.

All packages for ppc64le, x86, and x86_64 was linked with DT_RELR. This should have reduced size of compiled binares.

Python pre-compiled files (pyc) are now shipped in separate packages. It is now possible to avoid install those and save space by doing apk add !pyc.

UPGRADE NOTES
As always, make sure to use apk upgrade --available when switching between major versions.

CHANGES
The full list of changes can be found in the wiki, git log and bug tracker.

CREDITS
Thanks to everyone sending patches, bug reports, new and updated aports, and to everyone helping with writing documentation, maintaining the infrastructure, or contributing in any other way!

Thanks to GIGABYTE, Linode, Fastly, IBM, Equinix Metal, vpsFree and ungleich for providing us with hardware and hosting.

APORTS COMMIT CONTRIBUTORS
6543
AN3223
Adam Jensen
Adam Plumb
Adam Thiede
Aiden Grossman
Alex Denes
Alex Dowad
Alex McGrath
Alex Xu (Hello71)
Alexander Edland
Alexey Minnekhanov
Alexey Yerin
Andres Almiray
André Klitzing
Andy Hawkins
Andy Postnikov
Anjandev Momi
Antoine Martin
Antoni Aloy Torrens
Apo Apangona
Ariadne Conill
Armin Weigl
Arnav Singh
Bader Zaidan
Bart Ribbers
Ben Fuhrmannek
Bradford D. Boyle
Brian Cole
Brice
Bryan Kaplan
Camil Băncioiu
Carlo Landmeter
Catherine Schönhammer
Clayton Craft
Coco Liliace
Conrad Hoffmann
Consus
Cormac Stephenson
Cowington Post
Craig Andrews
Cédric Bellegarde
Daniel Fancsali
Dave Henderson
David Demelier
David Florness
David Wilson
Dekedro
Dermot Bradley
Dhruvin Gandhi
Djaker Abderrahmane
Dmitry Zakharchenko
Dominika Liberda
Dominique Martinet
DracoBlue
Drew DeVault
Duncan Bellamy
Dylan Van Assche
Dzmitry Sankouski
Edd Salkield
Eirik Furuseth
Elagost
Elly Fong-Jones
Eloi Torrents
Emma Nora Theuer
Fabricio Silva
Fiona Klute
FollieHiyuki
Francesco Colista
G.J.R Timmer
Galen Abell
Gary Holtz
Geod24
Glenn Strauss
Grigory Kirillov
Guillaume Quintard
Guy Broome
Guy Godfroy
Haelwenn (lanodan) Monnier
Henrik Grimler
Henrik Riomar
Hiroshi Kajisha
Hoang Nguyen
Holger Jaekel
Hoël Bézier
Hugo Osvaldo Barrera
Hugo Rodrigues
Hugo Wang
Hygna
Iskren Chernev
Iztok Fister Jr
Izumi Tsutsui
J0WI
Jacopo Mondi
Jake Buchholz Göktürk
Jakob Hauser
Jakob Meier
Jakub Jirutka
Jakub Panek
Jami Kettunen
Jason Swank
Jeff Dickey
Jeremy Saklad
Jinming Wu, Patrick
Johannes Heimansberg
John Gebbie
John Unland
John Vogel
Jonas
Jonas Heinrich
Jonas Marklén
Jordan Christiansen
Jordan ERNST
Josef Vybíhal
JuniorJPDJ
KAAtheWise
Kaarle Ritvanen
Karel Gardas
Kaspar Schleiser
Kate
Kay Thomas
Kevin Daudt
Klaus Frank
Klemens Nanni
Konstantin Kulikov
Krassy Boykinov
Krystian Chachuła
Laszlo Gombos
Lauren N. Liberda
Laurent Bercot
Lauri Tirkkonen
Leon Marz
Leon ROUX
Leonardo Arena
Linux User
Luca Weiss
Lucas Ramage
Lucidiot
MPThLee
Maarten van Gompel
Magnus Sandin
Marc0x1
Marco Schröder
Marian Buschsieweke
Mark Hills
Martijn Braam
Matthew T Hoare
Matthew Via
Maxim Karasev
Michael Ekstrand
Michael Pirogov
Michal Jirku
Michal Tvrznik
Michal Vasilek
Michał Polański
Mike Crute
Milan P. Stanić
Miles Alan
Natanael Copa
Nathan Angelacos
Newbyte
Nico de Haer
Nicolas Lorin
Noah Zalev
Noel Kuntze
Nulo
Oleg Titov
Oliver Smith
Olliver Schinagl
Orhun Parmaksız
Pablo Correa Gómez
Patrick Gansterer
Paul Bredbury
Peter Shkenev
Peter van Dijk
Petr Hodina
Petr Vorel
Philipp Arras
Piraty
ProgCat
Prokop Randacek
Quillith
R4SAS
Ralf Rachinger
Raymond Hackley
Rob Blanckaert
Rogério da Silva Yokomizo
Rosie K Languet
Rudolf Polzer
Saijin-Naib
Sascha Brawer
Sean McAvoy
Severin Neumann
Simon Frankenberger
Simon Rupf
Simon Zeni
Siva Mahadevan
Sodface
Stacy Harper
Stefan de Konink
Steffen Nurpmeso
Steve McMaster
Steven Honson
Stone Tickle
Sylvain Prat
Síle Ekaterin Liszka
Sören Tempel
Thomas Aldrian
Thomas Deutsch
Thomas Faughnan
Thomas Kienlen
Thomas Liske
TianYaX
Tim Magee
Tim Stanley
Timo Teräs
Timotej Lazar
Timothy Legge
Tom Lebreux
Tom Wieczorek
Uli Baum
Umar Getagazov
Valentin
Veikka Valtteri Kallinen
Wesley van Tilburg
Will Sinatra
William Desportes
William Walker
Willow Barraco
Wolf
Yuriy Chumak
Ziyao
alealexpro100
alice
build@apk-groulx
crapStone
dixyes
donoban
eugenefil
firefly-cpp
guddaff
j.r
knuxify
kpcyrd
leso-kn
lgehr
macmpi
messense
mio
nibon7
nu
omni
ovf
prspkt
psykose
ptrcnull
sales@ip2location.com
strophy
techknowlogick
tetsumaki
wdl
wener
xrs
Óliver García Albertos

ALPINE LINUX 3.17.3 RELEASED
The Alpine Linux project is pleased to announce the immediate availability of version 3.17.3 of its Alpine Linux operating system.

This release includes various security fixes, including:

openssl CVE-2023-0464
openssl CVE-2023-0465
The full lists of changes can be found in the git log.

GIT SHORTLOG
Alois Klink (3):
      community/ffmpeg: fix CVE-2022-3965
      community/ffmpeg: fix CVE-2022-3964
      main/tiff: add security patches

Andy Postnikov (7):
      community/php81-pecl-mongodb: upgrade to 1.15.1
      community/php81: security upgrade to 8.1.16
      community/php81-pecl-swoole: upgrade to 5.0.2
      community/phpldapadmin: upgrade to 1.2.6.5
      community/unit: upgrade to 1.29.1
      community/php81: upgrade to 8.1.17
      community/php81-pecl-xdebug: upgrade to 3.2.1

Antoine Martin (8):
      community/dotnet7-runtime: upgrade to 7.0.3
      community/dotnet7-build: upgrade to 7.0.103
      community/dotnet6-runtime: upgrade to 6.0.14
      community/dotnet6-build: upgrade to 6.0.114
      community/dotnet6-build: upgrade to 6.0.115
      community/dotnet6-runtime: upgrade to 6.0.15
      community/dotnet7-build: upgrade to 7.0.104
      community/dotnet7-runtime: upgrade to 7.0.4

Bart Ribbers (8):
      community/plasma: upgrade to 5.26.5
      community/osmscout-server: upgrade to 3.0.0
      community/kirigami-addons: upgrade to 0.6.1
      community/urfkill: set localestatedir to /var
      community/qmlkonsole: backport patch so it works with kirigami-addons 0.6
      community/qmlkonsole: bump pkgrel
      community/fprintd: enable on all architectures
      community/plasma-workspace: add missing dep on accountsservice and fprintd

Clayton Craft (4):
      community/vvmd: upgrade to 0.14
      community/chatty: upgrade to 0.7.0
      community/mtxclient: upgrade to 0.9.2
      community/nheko: upgrade to 0.11.3

Dermot Bradley (2):
      community/nomad: upgrade to 1.4.4
      community/nomad: upgrade to 1.4.6

Dmitry Zakharchenko (1):
      community/yt-dlp: upgrade to 2023.02.17

Duncan Bellamy (3):
      community/rspamd: upgrade to 3.5
      community/vectorscan: fix version number in header file
      community/rspamd: rebuild against vectorscan with correct version

Dylan Van Assche (1):
      community/dnsmasq: trigger pre-install script for all variants

Galen Abell (1):
      community/dino: security upgrade to 0.3.2

Grigory Kirillov (2):
      community/font-jetbrains-mono: upgrade to 2.304
      community/newsraft: upgrade to 0.17

Henrik Riomar (1):
      community/nats-server: upgrade to 2.9.15

Hoang Nguyen (1):
      community/translate-shell: upgrade to 0.9.7.1

Hoël Bézier (1):
      main/postgresql-common: fix pg_versions when setting default to latest

J0WI (2):
      main/apache2: security upgrade to 2.4.56
      community/openjdk8: security upgrade to 8.362.09

Jake Buchholz Göktürk (4):
      community/containerd: [3.17] security update to 1.6.18
      main/tiny-cloud: [3.17] update to 2.2.0
      main/tiny-cloud: [3.17] update to 2.2.1
      main/tiny-cloud: [3.17] update to 2.2.2

Jakub Jirutka (5):
      community/kea: fix running with supervise-daemon
      community/muacme: upgrade to 0.6.0
      main/libxslt: build static libs and add -static subpackage
      community/xdg-desktop-portal-gtk: fix missing org.gnome.desktop.lockdown
      community/zlib-ng: add secfix record for CVE-2022-37434

Jeff Snider (1):
      main/samba: upgrade to 4.16.9

Kaarle Ritvanen (4):
      community/zoneminder: security upgrade to 1.36.33
      community/zoneminder: add missing dependency
      community/zoneminder: fix zooming into events
      main/awall: upgrade to 1.12.2

Kevin Daudt (3):
      main/git: security upgrade to 2.38.4
      community/zabbix: include zabbix_js in -utils
      community/zabbix: upgrade to 6.2.7

Lauren N. Liberda (2):
      [3.17] community/yt-dlp: upgrade to 2023.03.04
      community/riot-web: security upgrade to 1.11.26

Leonardo Arena (2):
      community/nextcloud: upgrade to 25.0.4
      community/pg_probackup: upgrade to 2.5.11

Lucidiot (1):
      community/liferea: upgrade to 1.14.1

Michał Polański (8):
      community/caddy: upgrade to 2.6.4
      community/syft: upgrade to 0.72.0
      community/grype: upgrade to 0.57.1
      community/syft: upgrade to 0.73.0
      community/flatpak: upgrade to 1.14.3
      community/conmon: upgrade to 2.1.7
      community/grype: upgrade to 0.59.0
      community/syft: upgrade to 0.74.0

Milan P. Stanić (10):
      community/linux-edge: upgrade to 6.1.12
      main/haproxy: upgrade to 2.6.9
      community/linux-edge: upgrade to 6.2.0
      community/linux-edge: upgrade to 6.2.1
      community/linux-edge: upgrade to 6.2.2
      main/haproxy: upgrade to 2.6.10
      community/linux-edge: upgrade to 6.2.7
      main/haproxy: upgrade to 2.6.11
      community/linux-edge: upgrade to 6.2.8
      main/haproxy: upgrade to 2.6.12

Natanael Copa (67):
      main/linux-lts: upgrade to 5.15.94
      community/jool-modules-lts: rebuild against kernel 5.15.94-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.94-r0
      community/rtpengine-lts: rebuild against kernel 5.15.94-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.94-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.94-r0
      main/zfs-lts: rebuild against kernel 5.15.94-r0
      main/linux-lts: upgrade to 5.15.95
      community/jool-modules-lts: rebuild against kernel 5.15.95-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.95-r0
      community/rtpengine-lts: rebuild against kernel 5.15.95-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.95-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.95-r0
      main/zfs-lts: rebuild against kernel 5.15.95-r0
      main/samba: move libcluster-samba4.so to samba-libs
      main/linux-lts: upgrade to 5.15.96
      community/jool-modules-lts: rebuild against kernel 5.15.96-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.96-r0
      community/rtpengine-lts: rebuild against kernel 5.15.96-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.96-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.96-r0
      main/zfs-lts: rebuild against kernel 5.15.96-r0
      main/main/linux-lts: upgrade to 5.15.98
      community/jool-modules-lts: rebuild against kernel 5.15.98-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.98-r0
      community/rtpengine-lts: rebuild against kernel 5.15.98-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.98-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.98-r0
      main/zfs-lts: rebuild against kernel 5.15.98-r0
      main/main/linux-lts: upgrade to 5.15.99
      community/jool-modules-lts: rebuild against kernel 5.15.99-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.99-r0
      community/rtpengine-lts: rebuild against kernel 5.15.99-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.99-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.99-r0
      main/zfs-lts: rebuild against kernel 5.15.99-r0
      main/main/linux-lts: upgrade to 5.15.102
      community/jool-modules-lts: rebuild against kernel 5.15.102-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.102-r0
      community/rtpengine-lts: rebuild against kernel 5.15.102-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.102-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.102-r0
      main/zfs-lts: rebuild against kernel 5.15.102-r0
      main/main/linux-rpi: upgrade to 5.15.102
      community/jool-modules-rpi: rebuild against kernel 5.15.102-r0
      main/zfs-rpi: rebuild against kernel 5.15.102-r0
      main/asterisk: security upgrade to 18.15.1
      main/sofia-sip: security upgrade to 1.13.14 (CVE-2023-22741)
      main/sofia-sip: update secfixes data
      main/main/linux-lts: upgrade to 5.15.103
      community/jool-modules-lts: rebuild against kernel 5.15.103-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.103-r0
      community/rtpengine-lts: rebuild against kernel 5.15.103-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.103-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.103-r0
      main/zfs-lts: rebuild against kernel 5.15.103-r0
      main/main/linux-lts: upgrade to 5.15.104
      community/jool-modules-lts: rebuild against kernel 5.15.104-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.104-r0
      community/rtpengine-lts: rebuild against kernel 5.15.104-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.104-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.104-r0
      main/zfs-lts: rebuild against kernel 5.15.104-r0
      main/alpine-conf: backport fix for msdos efi
      main/mkinitfs: increase socket boffer to 4MB
      main/openssl: backport fix for CVE-2023-0466
      ===== release 3.17.3 =====

Newbyte (1):
      community/chatty: fix libcmatrix commit

Oliver Smith (5):
      community/pmbootstrap: upgrade to 1.51.0
      community/gpodder: upgrade to 3.11.1
      community/gpodder-adaptive: upgrade to 3.11.1
      community/gpodder: disable update check
      community/mrhlpr: upgrade to 1.2.0

Peter Shkenev (2):
      main/grub: make grub-mount independent of grub
      community/os-prober: add missing blkid and grub-mount dependencies

Síle Ekaterin Liszka (1):
      community/coeurl: upgrade to 0.3.0

Sören Tempel (3):
      community/go: upgrade to 1.19.6
      community/*: rebuild with go 1.19.6
      community/go: upgrade to 1.19.7

Thomas Liske (1):
      community/ifstate: upgrade to 1.8.2

Wesley van Tilburg (1):
      community/minify: upgrade to 2.12.5

knuxify (3):
      community/adw-gtk3: upgrade to 4.3
      community/strawberry: upgrade to 1.0.15
      community/prismlauncher: upgrade to 6.3

omni (2):
      community/qt5-qtwebengine: chromium security upgrade
      community/qt5-qtwebengine: chromium security upgrade

psykose (131):
      main/dhcpcd: disable privsep
      main/gnutls: patch CVE-2023-0361
      main/gnutls: ..bump pkgrel
      community/gtkmm4: fix segfault on init
      community/qbittorrent: upgrade to 4.5.1
      community/py3-django: upgrade to 3.2.18
      community/mutter: upgrade to 43.3
      community/firefox-esr: upgrade to 102.8.0
      main/intel-ucode: security upgrade to 20230214
      community/firefox: upgrade to 110.0
      Revert "community/firefox: upgrade to 110.0"
      community/gnome-boxes: upgrade to 43.3
      community/gnome-shell: upgrade to 43.3
      main/curl: backport CVE fixes
      community/webkit2gtk-5.0: upgrade to 2.38.5
      community/webkit2gtk-4.1: upgrade to 2.38.5
      community/webkit2gtk: upgrade to 2.38.5
      community/thunderbird: upgrade to 102.8.0
      community/gnome-backgrounds: upgrade to 43.1
      community/gnome-desktop: upgrade to 43.2
      community/gnome-firmware: upgrade to 43.2
      community/clamav: security upgrade to 0.105.2
      community/nodejs-current: upgrade to 19.6.1
      community/nodejs-current: fix patch
      main/nodejs: security upgrade to 18.14.1
      main/curl: bump rel
      community/mutter: backport xwayland patch
      main/pango: upgrade to 1.50.13
      community/epiphany: upgrade to 43.1
      main/tar: fix CVE-2022-48303
      community/phoc: backport crash fix patch for embedded wlroots
      community/chromium: upgrade to 110.0.5481.177
      community/networkmanager: upgrade to 1.40.16
      community/modemmanager: upgrade to 1.20.4
      community/avfs: upgrade to 1.1.5
      main/glib: upgrade to 2.74.6
      testing/gst-rtsp-server: upgrade to 1.20.6
      community/gst-editing-services: upgrade to 1.20.6
      community/gst-libav: upgrade to 1.20.6
      community/gst-plugins-bad: upgrade to 1.20.6
      community/gst-plugins-good: upgrade to 1.20.6
      community/gst-plugins-ugly: upgrade to 1.20.6
      community/gstreamer-vaapi: upgrade to 1.20.6
      main/gstreamer: upgrade to 1.20.6
      main/gst-plugins-base: upgrade to 1.20.6
      community/py3-gst: upgrade to 1.20.6
      main/nodejs: upgrade to 18.14.2
      community/nodejs-current: upgrade to 19.7.0
      community/sof-bin: upgrade to 2.2.4
      community/grilo-plugins: build lua factory
      community/libgit2: upgrade to 1.5.2
      community/gdm: fix path to touch in udev rule
      community/libass: fix buffer overrun
      community/mrhlpr: upgrade to 1.1.2
      main/curl: upgrade to 7.88.1
      community/sudo: fix potential double free
      community/sudo: add secfix
      community/libreswan: patch CVE-2023-23009
      main/redis: upgrade to 7.0.9
      main/git: backport patch to fix signed-tag oom
      community/libhandy1: upgrade to 1.8.2
      community/libadwaita: upgrade to 1.2.3
      community/libhandy1: skip ibus for tests
      main/opusfile: patch CVE-2022-47021
      main/e2fsprogs: security upgrade to 1.46.6
      community/buildkit: upgrade to 0.11.4
      community/emacs: backport secfix for desktop file
      community/emacs: backport second desktop-file patch
      community/fractal: upgrade to 4.4.2
      community/mpv: fix compat with new yt-dlp
      main/linux-lts: upgrade to 5.15.100
      community/jool-modules-lts: rebuild against kernel 5.15.100-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.100-r0
      community/rtpengine-lts: rebuild against kernel 5.15.100-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.100-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.100-r0
      main/zfs-lts: rebuild against kernel 5.15.100-r0
      main/linux-lts: upgrade to 5.15.101
      community/jool-modules-lts: rebuild against kernel 5.15.101-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.101-r0
      community/rtpengine-lts: rebuild against kernel 5.15.101-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.101-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.101-r0
      main/zfs-lts: rebuild against kernel 5.15.101-r0
      main/dovecot: add zstd compression support
      community/firefox-esr: upgrade to 102.9.0
      main/cmake: upgrade to 3.24.4
      main/llvm-runtimes: backport libc++ addition
      community/urfkill: create required service dir in package
      community/thunderbird: upgrade to 102.9.0
      main/nginx: mark CVE-2022-25345 invalid
      community/flatpak: upgrade to 1.14.4
      community/xorg-server: depend on mesa-egl, reformat
      main/curl: backport fixes
      main/squashfs-tools: use make install
      main/ccache: upgrade to 4.7.5
      main/redis: upgrade to 7.0.10
      community/openjdk8: remove broken unpack function
      community/libcamera: fix siggnature of camera ipa's
      main/lua-ldap: backport a crash fix
      main/openssl: fix CVE-2023-0464
      community/openssl1.1-compat: fix CVE-2023-0464
      community/openssl1.1-compat: fix cve patch
      community/libwpebackend-fdo: upgrade to 1.14.2
      main/tiff: fix some cves
      community/buildkit: upgrade to 0.11.5
      community/py3-tzdata: upgrade to 2023.2
      main/perl-datetime-timezone: upgrade to 2.58
      main/tzdata: upgrade to 2023b
      community/py3-tzdata: fix build
      community/py3-tzdata: downgrade to 2023.2
      main/perl-datetime-timezone: upgrade to 2.59
      community/runc: fix CVE-2023-27561
      community/jpegoptim: upgrade to 1.5.3
      main/py3-tz: upgrade to 2023.2
      community/ffmpeg: upgrade to 5.1.3
      community/zlib-ng: upgrade to 2.0.7
      community/pipewire: backport a fix for deadbeef
      main/tzdata: backport lebanon revert
      Revert "community/pipewire: backport a fix for deadbeef"
      community/pipewire: upgrade to 0.3.61
      community/pipewire: download patch to fix checksums
      community/chromium: upgrade to 111.0.5563.146
      main/patch: fix some overbig memory allocation
      main/openssl: patch CVE-2023-0465
      community/openssl1.1-compat: patch CVE-2023-0465
      main/openssl: fix checksum
      community/thunderbird: upgrade to 102.9.1
      main/tzdata: upgrade to 2023c
      main/libde265: patch cves
      main/dnsmasq: fix CVE-2023-28450

ptrcnull (2):
      community/xscreensaver: upgrade to 6.06
      community/miniflux: security upgrade to 2.0.43



ALPINE 3.14.10, 3.15.8 AND 3.16.5 RELEASED
The Alpine Linux project is pleased to announce the immediate availability of new stable releases:

3.14.10
3.15.8
3.16.5
Those releases include security fixes for openssl:

CVE-2023-0464
CVE-2023-0465

ALPINE 3.14.9, 3.15.7 AND 3.16.4 RELEASED
The Alpine Linux project is pleased to announce the immediate availability of new stable releases:

3.14.9
3.15.7
3.16.4
Those releases include security fixes for openssl:

CVE-2022-4203
CVE-2022-4304
CVE-2022-4450
CVE-2023-0215
CVE-2023-0216
CVE-2023-0217
CVE-2023-0286
CVE-2023-0401

ALPINE LINUX 3.17.3 RELEASED
The Alpine Linux project is pleased to announce the immediate availability of version 3.17.3 of its Alpine Linux operating system.

This release includes various security fixes, including:

openssl CVE-2023-0286
openssl CVE-2022-4304
openssl CVE-2022-4203
openssl CVE-2023-0215
openssl CVE-2022-4450
openssl CVE-2023-0216
openssl CVE-2023-0217
openssl CVE-2023-0401
The full lists of changes can be found in the git log.

GIT SHORTLOG

Andy Postnikov (2):
      community/php81: upgrade to 8.1.15
      community/phpmyadmin: security upgrade to 5.2.1

Antoine Martin (4):
      community/dotnet7-runtime: upgrade to 7.0.12
      community/dotnet7-build: upgrade to 7.0.102
      community/dotnet6-build: security upgrade to 6.0.113
      community/dotnet6-runtime: security upgrade to 6.0.13

Ariadne Conill (2):
      main/pkgconf: security upgrade to 1.9.4 (CVE-2023-24056)
      main/pkgconf: remove obsolete patch from sha512 checksums

Clayton Craft (1):
      community/chatty: upgrade to 0.7.0_rc5

Consus (1):
      main/multipath-tools: fix filepaths

Dermot Bradley (1):
      main/ifupdown-ng: add onlink option to default routes

Dhruvin Gandhi (3):
      community/hledger-interest: upgrade to 1.6.5
      community/hledger: upgrade to 1.28
      community/py3-debian: upgrade to 0.1.49

Duncan Bellamy (1):
      community/ceph16: upgrade to 16.2.11

Elagost (1):
      community/calls: update to 43.3

Francesco Colista (1):
      community/raft: upgrade to 0.16.0, disabled failing tests

Grigory Kirillov (1):
      community/newsraft: upgrade to 0.16

Henrik Riomar (3):
      community/netdata-go-plugins: upgrade to 0.50.0
      community/nats-server: upgrade to 2.9.12
      community/nats-server: upgrade to 2.9.14

Hoang Nguyen (3):
      community/gallery-dl: upgrade to 1.24.4
      community/nptsec: upgrade to 1.2.2
      community/gallery-dl: upgrade to 1.24.5

J0WI (2):
      main/apache2: security upgrade to 2.4.55
      community/upx: security upgrade to 4.0.2

Jake Buchholz Göktürk (1):
      community/docker-cli-compose: [3.17] security update to 2.15.1

Jakub Jirutka (1):
      community/pdns: rebuild

Jami Kettunen (1):
      community/waydroid: upgrade to 1.3.4

Kevin Daudt (2):
      community/git-machete: upgrade to 3.13.2
      main/newt: upgrade to 0.52.23

Leonardo Arena (2):
      community/nextcloud: upgrade to 25.0.3
      community/lxd: don't unmount systemd cgroup on stop

Michał Polański (1):
      community/conmon: upgrade to 2.1.6

Milan P. Stanić (9):
      community/linux-edge: upgrade to 6.1.4
      community/linux-edge: upgrade to 6.1.5
      community/linux-edge: upgrade to 6.1.6
      community/linux-edge: upgrade to 6.1.7
      community/linux-edge: upgrade to 6.1.8
      main/haproxy: upgrade to 2.6.8
      community/linux-edge: upgrade to 6.1.9
      community/linux-edge: upgrade to 6.1.10
      community/linux-edge: upgrade to 6.1.11

Natanael Copa (48):
      main/main/linux-lts: upgrade to 5.15.87
      community/jool-modules-lts: rebuild against kernel 5.15.87-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.87-r0
      community/rtpengine-lts: rebuild against kernel 5.15.87-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.87-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.87-r0
      main/zfs-lts: rebuild against kernel 5.15.87-r0
      main/main/linux-lts: upgrade to 5.15.88
      community/jool-modules-lts: rebuild against kernel 5.15.88-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.88-r0
      community/rtpengine-lts: rebuild against kernel 5.15.88-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.88-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.88-r0
      main/zfs-lts: rebuild against kernel 5.15.88-r0
      main/linux-rpi: upgrade to 5.15.88
      community/jool-modules-rpi: rebuild against kernel 5.15.88-r0
      main/zfs-rpi: rebuild against kernel 5.15.88-r0
      main/main/linux-lts: upgrade to 5.15.89
      community/jool-modules-lts: rebuild against kernel 5.15.89-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.89-r0
      community/rtpengine-lts: rebuild against kernel 5.15.89-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.89-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.89-r0
      main/zfs-lts: rebuild against kernel 5.15.89-r0
      main/main/linux-rpi: upgrade to 5.15.89
      community/jool-modules-rpi: rebuild against kernel 5.15.89-r0
      main/zfs-rpi: rebuild against kernel 5.15.89-r0
      community/libgit2: add secfixes comment for CVE-2023-22742
      main/main/linux-lts: upgrade to 5.15.90
      community/jool-modules-lts: rebuild against kernel 5.15.90-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.90-r0
      community/rtpengine-lts: rebuild against kernel 5.15.90-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.90-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.90-r0
      main/zfs-lts: rebuild against kernel 5.15.90-r0
      main/main/linux-rpi: upgrade to 5.15.90
      main/linux-lts: upgrade to 5.15.93
      community/jool-modules-lts: rebuild against kernel 5.15.93-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.93-r0
      community/rtpengine-lts: rebuild against kernel 5.15.93-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.93-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.93-r0
      main/zfs-lts: rebuild against kernel 5.15.93-r0
      main/linux-rpi: upgrade to 5.15.93
      community/jool-modules-rpi: rebuild against kernel 5.15.93-r0
      main/zfs-rpi: rebuild against kernel 5.15.93-r0
      main/alpine-conf: upgrade to 3.15.1
      ==== release 3.17.3 ====

Peter Shkenev (1):
      community/pipewire: bugfixes

Ralf Rachinger (1):
      community/gnome-builder: upgrade to 43.6

Simon Frankenberger (2):
      community/openjdk11: upgrade to 11.0.18
      community/openjdk17: upgrade to 17.0.6

Sören Tempel (2):
      community/go: upgrade to 1.19.5
      main/unbound: upgrade to 1.17.1

Thomas Liske (1):
      community/ifstate: upgrade to 1.8.1

macmpi (1):
      main/raspberrypi-bootloader: upgrade to 1.20230118

omni (6):
      community/newsboat: security upgrade to 2.30.1
      community/qt5-qtwebengine: chromium security upgrade
      community/tor: upgrade to 0.4.7.13
      community/qt5-qtwebengine: chromium security upgrade
      community/w3m: mitigate CVE-2022-38223
      community/qt5-qtwebengine: security upgrade to 5.15.12-lts

psykose (103):
      community/limine: upgrade to 4.20221230.0
      community/tracker-miners: upgrade to 3.4.3
      main/mesa: upgrade to 22.3.3
      community/networkmanager: upgrade to 1.40.10
      main/mesa: "downgrade" to 22.2.5
      main/curl: backport upstream fixes
      community/xfce4-screenshooter: upgrade to 1.10.3
      main/kamailio: upgrade to 5.6.3
      community/lldb: upgrade to 15.0.7
      community/openmp: upgrade to 15.0.7
      community/wasi-compiler-rt: upgrade to 15.0.7
      community/wasi-libcxx: upgrade to 15.0.7
      main/clang15: upgrade to 15.0.7
      main/lld: upgrade to 15.0.7
      main/llvm-runtimes: upgrade to 15.0.7
      main/llvm15: upgrade to 15.0.7
      main/net-snmp: mitigate cves
      main/ppp: mitigate CVE-2022-4603
      main/lxc: mitigate CVE-2022-47952
      main/redis: update secfixes
      community/pipewire: remove non-applying patch
      community/libinput: upgrade to 1.22.1
      community/firefox-esr: upgrade to 102.7.0
      community/firefox: upgrade to 109.0
      community/man-db: make trigger more quiet
      community/lxd: upgrade to 5.0.2
      main/lxc: upgrade to 5.0.2
      community/dqlite: upgrade to 1.13.0
      community/raft: disable another segfaulting test
      main/libxpm: security upgrade to 3.5.15
      community/cheese: upgrade to 43.0
      main/git: security upgrade to 2.38.3
      main/git: backport bundle segfault fix
      main/nagios: upgrade to 4.4.10
      community/orca: upgrade to 43.1
      community/gtksourceview5: upgrade to 5.6.2
      community/py3-license-expression: upgrade to 30.1.0
      community/sudo: security upgrade to 1.9.12_p2
      community/thunderbird: upgrade to 102.7.0
      community/chromium: upgrade to 109.0.5414.74
      community/libyang: upgrade to 2.1.30
      main/glib: upgrade to 2.74.5
      main/redis: upgrade to 7.0.8
      community/duply: upgrade to 2.4.2
      community/mpd: upgrade to 0.23.12
      community/gnome-desktop: upgrade to 43.1
      community/chromium: readd temp core patch
      community/libgit2: security upgrade to 1.5.1
      main/findutils: depend on self in -locate
      main/postfix: upgrade to 3.7.4
      main/libx11: backport fixes
      community/cmark: upgrade to 0.30.3
      community/evolution: rebuild against libcmark.so.0.30.3
      community/gnome-builder: rebuild against libcmark.so.0.30.3
      community/mkvtoolnix: rebuild against libcmark.so.0.30.3
      community/neochat: rebuild against libcmark.so.0.30.3
      community/nheko: rebuild against libcmark.so.0.30.3
      main/bind: security upgrade to 9.18.11
      community/networkmanager: upgrade to 1.40.12
      main/numactl: drop lto
      community/mpv: upgrade to 0.35.1
      main/zfs-rpi: rebuild against kernel 5.15.90-r0
      community/jool-modules-rpi: rebuild against kernel 5.15.90-r0
      community/firefox: upgrade to 109.0.1
      main/apr: security upgrade to 1.7.1
      community/thunderbird: upgrade to 102.7.1
      community/py3-django: upgrade to 3.2.17
      community/postgresql-timescaledb: upgrade to 2.9.2
      community/netifrc: fix commands in init.d
      main/openssh: backport double free fix
      main/libde265: upgrade to 1.0.11
      community/gnome-maps: upgrade to 43.4
      main/apr-util: upgrade to 1.6.3
      main/apr: upgrade to 1.7.2
      community/libhandy1: upgrade to 1.8.1
      community/webkit2gtk-5.0: upgrade to 2.38.4
      community/webkit2gtk-4.1: upgrade to 2.38.4
      community/webkit2gtk: upgrade to 2.38.4
      community/rustup: upgrade to 1.25.2
      main/libx11: upgrade to 1.8.4
      main/dhcpcd: add dhcpcd user
      community/sdl2: upgrade to 2.26.3
      community/xorg-server: security upgrade to 21.1.7
      community/nss: backport CVE-2022-3479 fix
      main/mariadb: upgrade to 10.6.12
      community/xwayland: upgrade to 22.1.8
      main/libtool: rebuild for gcc version
      main/openssl: security upgrade to 3.0.8
      community/openssl1.1-compat: security upgrade to 1.1.1t
      main/less: backport security fix
      community/libressl: backport security fix from errata 7.2-018
      community/py3-cryptography: patch CVE-2023-23931
      community/thunderbird: upgrade to 102.7.2
      community/libressl: upgrade to 3.6.2
      main/python3: upgrade to 3.10.10
      main/heimdal: fix CVE-2022-45142
      community/ghex: upgrade to 43.1
      community/emacs: patch CVE-2022-45939
      community/gnome-contacts: upgrade to 43.1
      community/postgresql12: upgrade to 12.14
      community/postgresql13: upgrade to 13.10
      main/postgresql14: upgrade to 14.7
      main/postgresql15: upgrade to 15.2

ptrcnull (5):
      community/gnome-chess: upgrade to 43.1
      community/gnome-text-editor: upgrade to 43.2
      community/highscore: build with libsoup3
      community/reuse: upgrade to 1.1.0
      community/gnote: upgrade to 43.1



ALPINE LINUX 3.17.1 RELEASED
The Alpine Linux project is pleased to announce the immediate availability of version 3.17.1 of its Alpine Linux operating system.

This release includes various security fixes, including:

openssl CVE-2022-3996
The full lists of changes can be found in the git log.

GIT SHORTLOG
Alex Dowad (1):
      community/lua-luautf8: upgrade to 0.1.5

André Klitzing (1):
      community/uncrustify: upgrade to 0.76.0

Andy Postnikov (8):
      community/php81: upgrade to 8.1.13
      community/php81-pecl-mongodb: upgrade to 1.15.0
      main/pcre2: upgrade to 10.41
      community/php81-pecl-xdebug: upgrade to 3.2.0
      main/pcre2: upgrade to 10.42
      community/php81-pecl-xhprof: upgrade to 2.3.9
      community/njs: upgrade to 0.7.9
      community/php81: security upgrade to 8.1.14 - CVE-2022-31631

Antoine Martin (7):
      community/dotnet7-stage0: enable s390x
      community/dotnet7-build: enable s390x
      community/dotnet7-runtime: enable s390x
      community/dotnet7-build: upgrade to 7.0.101
      community/dotnet7-runtime: upgrade to 7.0.1
      community/dotnet6-build: upgrade to 6.0.112
      community/dotnet6-runtime: upgrade to 6.0.12

Brice (1):
      community/lirc: fix missing sysmacros.h header

Clayton Craft (5):
      community/vvmd: upgrade to 0.13
      community/gnss-share: upgrade to 0.5
      community/modemmanager: add patch to fix broadmobi modems
      community/delve: move from testing
      community/mmsd-tng: upgrade to 2.1.0

Dermot Bradley (5):
      [3.17] community/cloud-init: re-enable LXD DataSource
      [3.17] community/cloud-init: revise README.Alpine
      main/ca-certificates: backport changes from upstream source
      main/ca-certificates: backport removal of "Do not edit" comment
      main/ca-certificates: backport remove unused option from trigger

Djaker Abderrahmane (1):
      community/inkscape: depend on adwaita-icon-theme

Duncan Bellamy (1):
      community/apache-arrow: upgrade to 10.0.1

FollieHiyuki (1):
      community/ntpsec: fix init script and default configuration file

Grigory Kirillov (1):
      community/newsraft: upgrade to 0.12

Guy Godfroy (3):
      community/prometheus: upgrade to 2.40.4
      community/prometheus-node-exporter: upgrade to 1.5.0
      community/prometheus: upgrade to 2.40.5

Henrik Riomar (3):
      community/nats-server: upgrade to 2.9.8
      community/nats-server: upgrade to 2.9.9
      community/nats-server: upgrade to 2.9.11

Hoang Nguyen (1):
      community/gallery-dl: upgrade to 1.24.2

J0WI (6):
      community/consul: security upgrade to 1.14.1
      community/java-postgresql-jdbc: security upgrade to 42.5.1
      main/vim: security upgrade to 9.0.0999
      community/vlc: security upgrade to 3.0.18
      community/xrdp: security upgrade to 0.9.21.1
      community/drupal7: upgrade to 7.94

Jake Buchholz Göktürk (1):
      community/containerd: [3.17] security upgrade to 1.6.12

Jakub Jirutka (3):
      main/ruby-debug: upgrade to 1.6.3
      main/ruby-rbs: upgrade to 2.7.0
      main/knot: upgrade to 3.2.4

Kevin Daudt (2):
      community/zabbix: upgrade to 6.2.4
      main/git: upgrade to 2.38.2

Lauren N. Liberda (1):
      community/riot-web: upgrade to 1.11.15

Leonardo Arena (1):
      community/nextcloud: upgrade to 25.0.2

Luca Weiss (1):
      community/yubioath-desktop: add missing dependencies

Marian Buschsieweke (2):
      community/gcc-avr: Fix linking with C++ & optimize for size
      community/gcc-avr: Finally fix compilation with C++

Michał Polański (12):
      community/crun: upgrade to 1.7.1
      community/crun: upgrade to 1.7.2
      community/buildah: upgrade to 1.28.2
      community/stylua: upgrade to 0.15.3
      community/netavark: upgrade to 1.4.0
      community/aardvark-dns: upgrade to 1.4.0
      community/xdg-desktop-portal: upgrade to 1.16.0
      testing/s3cmd: take over maintainership
      testing/s3cmd: upgrade to 2.3.0
      community/s3cmd: move from testing
      main/sqlite: upgrade to 3.40.1
      main/sqlite-tcl: upgrade to 3.40.1

Mike Crute (1):
      community/bird: migrate initd to supervise-daemon

Milan P. Stanić (7):
      community/linux-edge: upgrade to 6.0.10
      community/linux-edge: upgrade to 6.0.11
      main/haproxy: upgrade to 2.6.7
      community/linux-edge: upgrade to 6.0.12
      community/linux-edge: upgrade to 6.1.1
      community/linux-edge: upgrade to 6.1.2
      community/linux-edge: upgrade to 6.1.3

Natanael Copa (73):
      main/strongswan: add back patch for dmvpn
      community/inetutils-syslogd: remove post-{de,}install
      community/sxmo-xdm-config: remove pre-deinstall
      main/linux-lts: upgrade to 5.15.80
      community/jool-modules-lts: rebuild against kernel 5.15.80-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.80-r0
      community/rtpengine-lts: rebuild against kernel 5.15.80-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.80-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.80-r0
      main/zfs-lts: rebuild against kernel 5.15.80-r0
      main/abuild: upgrade to 3.10.0
      main/linux-rpi: upgrade to 5.15.80
      community/jool-modules-rpi: rebuild against kernel 5.15.80-r0
      main/zfs-rpi: rebuild against kernel 5.15.80-r0
      main/linux-lts: upgrade to 5.15.81
      community/jool-modules-lts: rebuild against kernel 5.15.81-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.81-r0
      community/rtpengine-lts: rebuild against kernel 5.15.81-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.81-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.81-r0
      main/zfs-lts: rebuild against kernel 5.15.81-r0
      main/linux-rpi: upgrade to 5.15.81
      community/jool-modules-rpi: rebuild against kernel 5.15.81-r0
      main/zfs-rpi: rebuild against kernel 5.15.81-r0
      main/tinyproxy: fix secfixes comment
      main/libarchive: backport fix for CVE-2022-36227
      main/libarchive: bump pkgrel
      main/linux-lts: upgrade to 5.15.82
      community/jool-modules-lts: rebuild against kernel 5.15.82-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.82-r0
      community/rtpengine-lts: rebuild against kernel 5.15.82-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.82-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.82-r0
      main/zfs-lts: rebuild against kernel 5.15.82-r0
      main/linux-rpi: upgrade to 5.15.82
      community/jool-modules-rpi: rebuild against kernel 5.15.82-r0
      main/zfs-rpi: rebuild against kernel 5.15.82-r0
      main/linux-lts: upgrade to 5.15.83
      community/jool-modules-lts: rebuild against kernel 5.15.83-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.83-r0
      community/rtpengine-lts: rebuild against kernel 5.15.83-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.83-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.83-r0
      main/zfs-lts: rebuild against kernel 5.15.83-r0
      main/linux-rpi: upgrade to 5.15.83
      community/jool-modules-rpi: rebuild against kernel 5.15.83-r0
      main/zfs-rpi: rebuild against kernel 5.15.83-r0
      main/linux-lts: upgrade to 5.15.84
      community/jool-modules-lts: rebuild against kernel 5.15.84-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.84-r0
      community/rtpengine-lts: rebuild against kernel 5.15.84-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.84-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.84-r0
      main/zfs-lts: rebuild against kernel 5.15.84-r0
      main/main/linux-lts: upgrade to 5.15.85
      community/jool-modules-lts: rebuild against kernel 5.15.85-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.85-r0
      community/rtpengine-lts: rebuild against kernel 5.15.85-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.85-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.85-r0
      main/zfs-lts: rebuild against kernel 5.15.85-r0
      main/main/linux-lts: upgrade to 5.15.86
      community/jool-modules-lts: rebuild against kernel 5.15.86-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.86-r0
      community/rtpengine-lts: rebuild against kernel 5.15.86-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.86-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.86-r0
      main/zfs-lts: rebuild against kernel 5.15.86-r0
      main/linux-rpi: upgrade to 5.15.86
      community/jool-modules-rpi: rebuild against kernel 5.15.86-r0
      main/zfs-rpi: rebuild against kernel 5.15.86-r0
      main/perl-type-tiny: fix for 32 bit arches
      ===== release 3.17.1 =====

Newbyte (3):
      main/mesa: revert patch causing problems with Mali GPUs
      community/karlender: upgrade to 0.8.0
      community/gnome-control-center: upgrade to 43.2

Oliver Smith (5):
      community/pmbootstrap: upgrade to 1.50.1
      community/mrhlpr: upgrade to 1.1.1
      community/megapixels: upgrade to 1.6.0
      community/megapixels: downgrade to 1.5.2
      main/util-linux: fix rfkill.initd initial restore

Pablo Correa Gómez (7):
      community/gnome-software: point to v3.17 appstream
      community/appstream: add /var/cache/swcatalog/xml to triggers
      community/gnome-control-center: fix crash in connection-editor
      community/calls: upgrade to 43.2 and update source
      community/cheese: upgrade to 43.0
      community/gnome-initial-setup: upgrade to 43.2
      community/gnome-remote-desktop: upgrade to 43.2

Ralf Rachinger (1):
      community/nextcloud: use php81 in scripts and mentions

Simon Frankenberger (1):
      community/proftpd: upgrade to 1.3.7f

Sören Tempel (7):
      community/libcoap: upgrade to 4.3.1
      community/cabal: depend on curl
      community/opensmtpd: move from main
      main/opensmtpd: link against libressl
      community/booster: backport module normalization patch
      community/go: upgrade to 1.19.4
      community/*: rebuild with go 1.19.4

Thomas Kienlen (1):
      main/ruby: security upgrade to 3.1.3

Timo Teräs (1):
      community/linux-edge: enable pinctrl cannonlake/tigerlake on x86_64

Will Sinatra (1):
      community/fennel: add luajit support

knuxify (1):
      community/blueman: upgrade to 2.3.5

macmpi (1):
      main/linux-firmware: update Pi Bluetooth to 1.2-4+rpt10

omni (13):
      main/zfs: upgrade to 2.1.7
      main/zfs-lts: upgrade to 2.1.7
      main/zfs-rpi: upgrade to 2.1.7
      community/qt5-qtwebengine: chromium security upgrade
      community/qt5-qtwebengine: chromium security upgrade
      community/tor: upgrade to 0.4.7.12
      community/qt5-qtwebengine: chromium security upgrade
      community/qt5-qtwebengine: chromium security upgrade
      main/knot: upgrade to 3.2.3
      main/mbedtls: upgrade to 2.28.2
      community/qt5-qtwebengine: chromium security upgrade
      main/xen: security upgrade to 4.16.3
      community/qt5-qtwebengine: chromium security upgrade

prspkt (1):
      community/qbittorrent: upgrade to 4.5.0

psykose (163):
      community/ceph16: fix toplevel depends
      community/ceph17: add version to toplevel depends
      community/chromium: upgrade to 107.0.5304.121
      main/glib: upgrade to 2.74.2
      main/btrfs-progs: upgrade to 6.0.2
      community/b3sum: upgrade to 1.3.3
      community/font-iosevka: upgrade to 16.5.0
      community/xmlsec: upgrade to 1.2.37
      community/xpra: upgrade to 4.4.3
      community/firefox: upgrade to 107.0.1
      community/openmp: upgrade to 15.0.6
      community/wasi-compiler-rt: upgrade to 15.0.6
      community/wasi-libcxx: upgrade to 15.0.6
      main/clang15: upgrade to 15.0.6
      main/lld: upgrade to 15.0.6
      main/llvm-runtimes: upgrade to 15.0.6
      main/llvm15: upgrade to 15.0.6
      community/nodejs-current: upgrade to 19.2.0
      community/flatpak-builder: upgrade to 1.2.3
      main/xz: upgrade to 5.2.9
      main/texinfo: upgrade to 7.0.1
      main/bash: upgrade to 5.2.12
      community/networkmanager: upgrade to 1.40.6
      community/thunderbird: upgrade to 102.5.1
      community/iotop: fix upgrade conflict
      community/py3-configobj: fix upgrade conflict
      community/iotop: fix type in pre-upgrade for /
      community/sdl2: upgrade to 2.26.1
      community/xdg-desktop-portal-gtk: upgrade to 1.14.1
      community/gnome-maps: upgrade to 43.2
      main/glib: upgrade to 2.74.3
      community/libshumate: upgrade to 1.0.3
      main/openrc: mention procps-doc for the sysctl.d readme
      community/font-iosevka: upgrade to 16.6.0
      community/shotwell: upgrade to 0.31.7
      main/graphviz: upgrade to 7.0.4
      community/firefox: depend on some non-traced libraries
      main/vulkan-loader: upgrade to 1.3.231.2
      community/swaync: upgrade to 0.7.3
      community/tracker: upgrade to 3.4.2
      community/tracker-miners: upgrade to 3.4.2
      community/gnome-characters: upgrade to 43.1
      main/apr-util: attempt to fix ndbm
      community/pulseaudio: depend on alsa-utils in -openrc
      main/rsyslog: upgrade to 8.2212.0
      community/audacity: upgrade to 3.2.2
      main/py3-certifi: upgrade to 2022.12.7
      community/ansible-lint: upgrade to 6.9.1
      main/freetds: upgrade to 1.3.16
      community/fwupd: upgrade to 1.8.8
      main/mesa: upgrade to 22.2.5
      main/python3: upgrade to 3.10.9
      community/gnome-menus: enable introspection
      community/chromium: upgrade to 108.0.5359.98
      community/font-iosevka: upgrade to 16.7.0
      main/python3: make python symlink relative
      main/makedepend: upgrade to 1.0.8
      community/geary: disable libunwind
      main/redis: upgrade to 7.0.6
      community/nautilus: upgrade to 43.1
      community/mutter: upgrade to 43.2
      community/gnome-shell: upgrade to 43.2
      community/exempi: upgrade to 2.6.3
      community/evolution-ews: upgrade to 3.46.2
      community/evolution: upgrade to 3.46.2
      community/evolution-data-server: upgrade to 3.46.2
      community/xorg-server: security upgrade to 21.1.5
      community/lego: disable check
      main/bash: upgrade to 5.2.15
      main/py3-lxml: security upgrade to 4.9.2
      community/gnome-bluetooth: upgrade to 42.5
      community/xwayland: security upgrade to 22.1.6
      community/xorg-server: correct cve number
      main/glib: backport gvariant handling security fixes
      community/chromium: upgrade to 108.0.5359.124
      community/weston: upgrade to 11.0.1
      community/nodejs-current: upgrade to 19.3.0
      main/attr: add static subpackage
      main/glib: backport another security patch
      main/libogg: add static library
      community/apache-arrow: add missing pyarrow deps, fix plasma_store
      community/apache-arrow: rename py3-apache-arrow to py3-pyarrow
      community/apache-arrow: fix the provides
      main/linux-firmware: upgrade to 20221214
      main/libx11: upgrade to 1.8.3
      main/samba: upgrade to 4.16.8
      main/help2man: upgrade to 1.49.3
      community/jupyter-notebook: remove nonexistent mathjax2
      community/gedit-plugins: rebuild for gedit
      community/font-iosevka: upgrade to 16.8.0
      community/thunderbird: upgrade to 102.6.0
      community/firefox-esr: upgrade to 102.6.0
      community/chromium: upgrade to 108.0.5359.125
      community/gnome-firmware: upgrade to 43.1
      community/chromium: fix checksums
      community/limine: upgrade to 4.20221216.0
      testing/libgdiplus: take over maintainership
      community/libgdiplus: move from testing
      community/chromium: readd patch
      community/networkmanager: upgrade to 1.40.8
      community/vte3: upgrade to 0.70.2
      community/font-iosevka: upgrade to 16.8.1
      main/redis: upgrade to 7.0.7
      community/font-iosevka: upgrade to 16.8.2
      community/firefox: upgrade to 108.0.1
      main/ca-certificates: allow replacing libcrypto1.1 /etc/ssl1.1/ certs
      community/font-iosevka: upgrade to 16.8.3
      community/xorg-server: upgrade to 21.1.6
      community/xwayland: upgrade to 22.1.7
      main/gstreamer: upgrade to 1.20.5
      main/gst-plugins-base: upgrade to 1.20.5
      community/gst-plugins-good: upgrade to 1.20.5
      community/gst-plugins-bad: upgrade to 1.20.5
      community/gst-plugins-ugly: upgrade to 1.20.5
      community/gst-editing-services: upgrade to 1.20.5
      community/gstreamer-vaapi: upgrade to 1.20.5
      community/py3-gst: upgrade to 1.20.5
      community/gst-libav: upgrade to 1.20.5
      testing/gst-rtsp-server: upgrade to 1.20.5
      community/font-iosevka: upgrade to 16.8.4
      community/thunderbird: upgrade to 102.6.1
      community/fetchmail: upgrade to 6.4.34
      main/curl: upgrade to 7.87.0
      main/bind: upgrade to 9.18.10
      main/gtk+3.0: upgrade to 3.24.36
      community/gnome-boxes: upgrade to 43.2
      main/dovecot: upgrade to 2.3.20
      community/libplacebo: backport fixes for mpv colors
      main/libksba: security upgrade to 1.6.3
      community/webkit2gtk: upgrade to 2.38.3
      community/webkit2gtk-4.1: upgrade to 2.38.3
      community/webkit2gtk-5.0: upgrade to 2.38.3
      community/gtk4.0: upgrade to 4.8.3
      community/dovecot-fts-xapian: rebuild against dovecot
      main/graphviz: upgrade to 7.0.5
      community/libgusb: upgrade to 0.4.3
      main/glib: upgrade to 2.74.4
      main/rsync: remove duplicate cve
      community/monero: disable march=native
      community/firefox: remove fno-plt
      community/firefox-esr: remove fno-plt
      community/thunderbird: remove fno-plt
      community/vlc: remove fno-plt
      community/sdl2: upgrade to 2.26.2
      main/openssl: patch CVE-2022-3996
      main/zlib: update download location
      main/json-c: add -static
      main/json-c: unsplit static
      community/firefox: upgrade to 108.0.2
      community/libplacebo: upgrade to 5.229.2
      community/libwnck3: backport crash fix
      community/qt6-*: upgrade to 6.4.2
      community/sushi: fix depends
      community/libadwaita: upgrade to 1.2.1
      community/gvfs: upgrade to 1.50.3
      community/evolution-ews: upgrade to 3.46.3
      community/evolution: upgrade to 3.46.3
      community/evolution-data-server: upgrade to 3.46.3
      community/gnome-maps: upgrade to 43.3
      community/eog: upgrade to 43.2
      community/bird: add dbg
      community/nautilus: upgrade to 43.2
      community/gnome-remote-desktop: upgrade to 43.3

ptrcnull (1):
      community/ruby-nokogiri: upgrade to 1.13.10


ALPINE LINUX 3.17.0 RELEASED
We are pleased to announce the release of Alpine Linux 3.17.0, the first in the v3.17 stable series.

HIGHLIGHTS
bash 5.2
GCC 12
Kea 2.2
LLVM 15
OpenSSL 3.0
Perl 5.36
PostgreSQL 15
Node.js (lts) 18.12
Node.js (current) 19.1
Ceph 17.2
GNOME 43
Go 1.19
KDE Plasma 5.26
Rust 1.64
.NET 7.0.100
SIGNIFICANT CHANGES
OpenSSL 3.0 is now the default OpenSSL version. OpenSSL 1.1 is available via the openssl1.1-compat package.

Rust is now available on all supported architectures.

UPGRADE NOTES
As always, make sure to use apk upgrade --available when switching between major versions.

DEPRECATION NOTES
PHP 8.0 has been deprecated.

ISC Kea moved to main repository for long time support while ISC dhcp moved to community repository. Users of dhcpd are encouraged to migrate to Kea.

CHANGES
The full list of changes can be found in the wiki, git log and bug tracker.

CREDITS
Thanks to everyone sending patches, bug reports, new and updated aports, and to everyone helping with writing documentation, maintaining the infrastructure, or contributing in any other way!

Thanks to GIGABYTE, Linode, Fastly, IBM, Equinix Metal, vpsFree for providing us with hardware and hosting.

APORTS COMMIT CONTRIBUTORS
2cgc5h
3np
6543
Adam Jensen
Adam Saponara
Adam Thiede
Adrián Arroyo Calle
Aiden Grossman
Aleksei Nikiforov
Alex Denes
Alex Dowad
Alex McGrath
Alex Ryndin
Alex Xu (Hello71)
Alexander Brzoska
Alexander Mazuruk
Alexey Yerin
Andreas Kemnade
Andrei Jiroh Halili
Andrei Zavada
André Klitzing
Andy Hawkins
Andy Postnikov
Anjandev Momi
Antoine Martin
Anton Bambura
Antoni Aloy Torrens
Ariadne Conill
Arnavion
Aron Barath
Avis Orsetti
Bart Ribbers
Ben Westover
Bobby The Builder
Boris Faure
Bradford D. Boyle
Brian Vuyk
Caleb Connolly
Carlo Landmeter
Carmina16
ChemicalXandco
Chris Talbot
Christian Kohlschütter
Clayton Craft
Conrad Hoffmann
Consus
Daisuke Mizobuchi
Damian Kurek
Daniel Mizyrycki
Daniel Moch
Daniel Tobon
Daniele Parisi
Danny McClanahan
Dave Henderson
David Demelier
David Florness
David Heidelberg
Dekedro
Dermot Bradley
Devin Lin
Devin Stewart
Dhruvin Gandhi
Dmitry Zakharchenko
Dominika Liberda
Dominique Martinet
Drew DeVault
Duncan Bellamy
Dylan Van Assche
Edd Salkield
Elly Fong-Jones
Eloi Torrents
Emanuele Sorce
Eric Nemchik
Eric Roshan-Eisner
Fabian Affolter
Fiona Klute
FollieHiyuki
Francesco Camuffo
Francesco Colista
Frank Tributh
Gabriel Sanches
Galen Abell
Gavin Henry
Glenn Strauss
GreyXor
Grigory Kirillov
Guillaume Quintard
Guy Godfroy
Haelwenn (lanodan) Monnier
Hani Shawa
Henrik Grimler
Henrik Riomar
Holger Jaekel
Hugo Rodrigues
Hugo Wang
Ian Bashford
Ingo
Iskren Chernev
Iztok Fister Jr
J0WI
Jacob Panek
Jake Buchholz Göktürk
Jakob Hauser
Jakob Meier
Jakub Jirutka
Jakub Panek
Jan Jasper de Kroon
Jason Hall
Jeff Dickey
Jeremy Grosser
John Vogel
Jonas
Jonas Marklén
Jordan Christiansen
Jordan ERNST
JuniorJPDJ
Justin Berthault
Justin Klaassen
Kaarle Ritvanen
Kate
Kay Thomas
Kevin Daudt
Konstantin Kulikov
Krystian Chachuła
Lars Kellogg-Stedman
Laszlo Gombos
Lauren N. Liberda
Laurent Bercot
Lauri Tirkkonen
Leo
Leon Marz
Leonardo Arena
Luca Weiss
Lucas Ramage
Lucidiot
Maarten van Gompel
Magnus Sandin
Malte Voos
Marc Hassan
Marco Schröder
Marian Buschsieweke
Marino Pascual
Mark Pashmfouroush
Markus Kolb
Marten Ringwelski
Martijn Braam
Martin Thielecke
Martin Uddén
Marvin Preuss
Matthew T Hoare
Maxim Karasev
Michael Ekstrand
Michael Lyngbol
Michael Pirogov
Michael Truog
Michael Zimmermann
Michal Jirku
Michal Tvrznik
Michał Adamski
Michał Polański
Milan P. Stanić
Miles Alan
Minecrell
Mohammad Abdolirad
Natanael Copa
Nathan Rennie-Waldock
Newbyte
Ngô Ngọc Đức Huy
NickBug
Nico Schottelius
Nicolas Lorin
Noel Kuntze
Nulo
Oleg Titov
Oliver Smith
Olliver Schinagl
Otto Modinos
Pablo Correa Gómez
Patrick Gansterer
Paul Bredbury
Paul Spooren
Paulo Luna
Peter Shkenev
Peter van Dijk
Petr Fedchenkov
Philipp Arras
Pranjal Kole
Przemysław Romanik
QShen3
R4SAS
Ralf Rachinger
Rasmus Thomsen
Raymond Hackley
Risgit
Rob Blanckaert
Robert Adam
Robert Günzler
Rosie K Languet
Rudolf Polzer
Saarko
Saarko Sandomir
Saijin-Naib
Sam Whited
Sascha Brawer
Sashanoraa
Scott Robinson
Sean McAvoy
Sebastian Meyer
Sergey S
Simon Frankenberger
Simon Rupf
Simon Ser
Simon Zeni
Sodface
Stacy Harper
Stanislav Kholmanskikh
Steffen Nurpmeso
Stephen Abbene
Steve McMaster
Steven Honson
Stone Tickle
Sylvain Prat
Síle Ekaterin Liszka
Sören Tempel
TBK
Taner Tas
Thiago Perrotta
Thomas Deutsch
Thomas Faughnan
Thomas Kienlen
Thomas Liske
Tim Stanley
Timo Brasz
Timo Teräs
Timotej Lazar
Timothy Legge
Tom Tsagk
Tom Wieczorek
Tomio
Uli Roth
Umar Getagazov
Valery Ushakov
Wen Heping
Wesley van Tilburg
Will Sinatra
William Desportes
Wolf
Wolfgang Walther
Yann Autissier
Yo'av Moshe
Zach DeCook
Ziyao
alealexpro100
alice
alikates
ant
build@apk-groulx
crapStone
donoban
firefly-cpp
gay
guddaff
itd
j.r
james palmer
jenneron
jminer
jpdw34
knuxify
kpcyrd
kt programs
macmpi
messense
mio
misthios
mochaaP
nadvagauser
nibon7
omni
prspkt
psykose
ptrcnull
rubicon
skovati
takumin
techknowlogick
tetsumaki
tiotags
urain39
vin01
wener
xrs
Óliver García
Óliver García Albertos


ALPINE LINUX 3.16.3 RELEASED
The Alpine Linux project is pleased to announce the immediate availability of version 3.16.3 of its Alpine Linux operating system.

This is a bugfix release.

The full lists of changes can be found in the git log.

GIT SHORTLOG
6543 (1):
      community/gitea: upgrade to 1.17.3

Andy Postnikov (14):
      main/postgresql13: security upgrade to 13.8 - CVE-2022-2625
      main/postgresql14: security upgrade to 14.5 - CVE-2022-2625
      community/postgresql12: security upgrade to 12.12 - CVE-2022-2625
      community/phpldapadmin: upgrade to 1.2.6.4
      community/composer: upgrade to 2.4.1
      community/drupal7: upgrade to 7.92
      community/composer: upgrade to 2.4.2
      community/php8: security upgrade to 8.0.24
      community/php81: security upgrade to 8.1.11
      community/php8: security upgrade to 8.0.25
      community/php81: security upgrade to 8.1.12
      community/php8-pecl-xhprof: upgrade to 2.3.8
      community/php81-pecl-xhprof: upgrade to 2.3.8
      community/konsole: remove stale patch from checksums

Anjandev Momi (1):
      community/sxmo-utils: upgrade to 1.9.1

Antoine Martin (10):
      community/dotnet6-runtime: security upgrade to 6.0.8
      community/dotnet6-build: security upgrade to 6.0.108
      community/dotnet6-build: fix RID bug
      community/dotnet6-runtime: fix RID bug
      community/dotnet6-build: upgrade to 6.0.109
      community/dotnet6-runtie: upgrade to 6.0.9
      community/dotnet6-build: security upgrade to 6.0.110
      community/dotnet6-runtime: security upgrade to 6.0.10
      community/dotnet6-build: upgrade to 6.0.111
      community/dotnet6-runtime: upgrade to 6.0.11

Ariadne Conill (1):
      main/alpine-baselayout: restore nsswitch.conf

Bart Ribbers (3):
      community/kopeninghours: new aport
      community/kosmindoormap: depend on kopeninghours
      community/kde-release-service: upgrade to 22.04.3

Clayton Craft (1):
      community/superd: upgrade to 0.6

Dmitry Zakharchenko (2):
      community/py3-tzdata: new aport
      community/py3-pendulum: new aport

Duncan Bellamy (2):
      community/ceph: add py3-ceph-common sub package with core ceph module
      community/rspamd: upgrade to 3.3

Galen Abell (1):
      community/riot-web: security upgrade to 1.11.4

Guillaume Quintard (2):
      main/varnish: upgrade to 7.1.1
      main/varnish: upgrade to 7.1.2

Henrik Riomar (2):
      main/intel-ucode: security upgrade to 20220809
      community/vault: upgrade to 1.10.6

Holger Jaekel (2):
      community/gdal: upgrade to 3.5.3
      community/geos: upgrade to 3.10.3

J0WI (23):
      community/java-postgresql-jdbc: security upgrade to 42.4.2
      main/mariadb: security upgrade to 10.6.9
      community/fdkaac: security upgrade to 1.0.3
      main/dhcp: security upgrade to 4.4.3_p1
      community/imagemagick6: security upgrade to 6.9.12.65
      community/imagemagick: upgrade to 7.1.0.50
      community/vault: security upgrade to 1.10.7
      main/git: security upgrade to 2.36.3
      main/mariadb: upgrade to 10.6.10
      community/py3-django: security upgrade to 3.2.16
      main/nginx: security upgrade to 1.22.1
      community/geth: security upgrade to 1.10.22
      main/darkhttpd: add secfixes
      community/e2guardian: security upgrade to 5.4.5r
      community/libreoffice: patch CVE-2022-3140
      community/erlang: security upgrade to 24.3.4.6
      main/py3-mako: add secfixes
      community/libmodbus: security upgrade to 3.1.8
      community/faad2: security upgrade to 2.10.1
      community/py3-waitress: add secfixes
      community/py3-bottle: security upgrade to 0.12.21
      main/py3-tz: upgrade to 2022.2.1
      main/py3-tz: upgrade to 2022.6

Jake Buchholz Göktürk (5):
      community/runc: upgrade to 1.1.4
      community/containerd: upgrade to 1.6.8
      community/docker; security upgrade to 20.10.18
      community/docker: security upgrade to 20.10.20
      community/docker-cli-compose: security upgrade to 2.12.2

Jakub Jirutka (15):
      main/ruby-bundler: fix --help when man is avail but -doc isn't installed
      main/alpine-make-rootfs: upgrade to 0.6.1
      community/open-vm-tools: security upgrade to 12.1.0
      main/luajit: build with -O2 instead of -Os
      community/docker-registry: add missing depend() to init script
      community/knot-resolver: fix running w/ supervise-daemon, add provide dns
      community/stunnel: disable test p02_require_cert on s390x (hangs)
      community/alpine-make-vm-image: upgrade to 0.10.0
      main/knot: upgrade to 3.1.9
      main/nodejs: fix secfixes
      community/linux-edge: enable CONFIG_NFT_OBJREF
      main/linux-lts: enable missing nftables options
      main/openldap: unify changes and patches for slapd.conf and slapd.ldif
      main/openldap: fix problem with pidfile - service status crashed
      main/openldap: fix invalid includes in slapd.conf

Jordan Christiansen (1):
      community/acme-client: upgrade to 1.3.1

Kaarle Ritvanen (4):
      community/zoneminder: fix various issues
      community/zoneminder: fix init script
      main/logrotate: subpackage for main syslog file
      main/awall: upgrade to 1.12.1

Kevin Daudt (3):
      community/zabbix: explicitly set PluginSocket for agent2
      community/zabbix: include default plugin conf
      community/zabbix: upgrade to 6.0.8

Konstantin Kulikov (4):
      community/grafana-frontend: upgrade to 8.5.11
      community/grafana: upgrade to 8.5.11
      community/grafana-frontend: upgrade to 8.5.13
      community/grafana: security upgrade to 8.5.13

Lauren N. Liberda (1):
      community/riot-web: security upgrade to 1.11.8

Leonardo Arena (4):
      community/nextcloud: upgrade to 24.0.5
      community/nextcloud23: upgrade to 23.0.9
      community/zabbix: upgrade to 6.0.9
      main/protobuf-c: upgrade to 1.4.1

Marc Hassan (1):
      main/nodejs: upgrade to 16.17.1

Michał Polański (2):
      community/buildah: upgrade to 1.26.4
      community/buildah: upgrade to 1.26.5

Milan P. Stanić (25):
      community/linux-edge: upgrade to 5.19.1
      community/linux-edge: remove edge4virt flavor, use linux-edge in VMs
      main/haproxy: upgrade to 2.4.18
      community/linux-edge: upgrade to 5.19.2
      community/linux-edge: upgrade to 5.19.3
      community/linux-edge: upgrade to 5.19.4
      community/linux-edge: fix openssl in makedepends
      community/linux-edge: upgrade to 5.19.6
      community/linux-edge: upgrade to 5.19.7
      community/linux-edge: upgrade to 5.19.8
      community/linux-edge: upgrade to 5.19.9
      community/linux-edge: remove provides/replaces linux-edeg4virt
      community/linux-edge: upgrade to 5.19.10
      community/linux-edge: upgrade to 5.19.11
      community/linux-edge: upgrade to 5.19.12
      community/linux-edge: upgrade to 6.0.0
      community/linux-edge: add speakup patch
      community/linux-edge: upgrade to 6.0.1
      community/linux-edge: upgrade to 6.0.2
      community/linux-edge: upgrade to 6.0.3
      community/linux-edge: upgrade to 6.0.5
      community/linux-edge: upgrade to 6.0.6
      community/linux-edge: fix build on x86_64
      community/linux-edge: upgrade to 6.0.7
      community/linux-edge: upgrade to 6.0.8

Natanael Copa (138):
      main/linux-lts: upgrade to 5.15.60
      community/jool-modules-lts: rebuild against kernel 5.15.60-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.60-r0
      community/rtpengine-lts: rebuild against kernel 5.15.60-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.60-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.60-r0
      main/zfs-lts: rebuild against kernel 5.15.60-r0
      main/linux-lts: upgrade to 5.15.61
      community/jool-modules-lts: rebuild against kernel 5.15.61-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.61-r0
      community/rtpengine-lts: rebuild against kernel 5.15.61-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.61-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.61-r0
      main/zfs-lts: rebuild against kernel 5.15.61-r0
      main/linux-lts: upgrade to 5.15.62
      community/jool-modules-lts: rebuild against kernel 5.15.62-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.62-r0
      community/rtpengine-lts: rebuild against kernel 5.15.62-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.62-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.62-r0
      main/zfs-lts: rebuild against kernel 5.15.62-r0
      main/linux-lts: backport patch for xen issue
      community/jool-modules-lts: rebuild against kernel 5.15.62-r1
      community/rtl8821ce-lts: rebuild against kernel 5.15.62-r1
      community/rtpengine-lts: rebuild against kernel 5.15.62-r1
      main/dahdi-linux-lts: rebuild against kernel 5.15.62-r1
      main/xtables-addons-lts: rebuild against kernel 5.15.62-r1
      main/zfs-lts: rebuild against kernel 5.15.62-r1
      main/linux-lts: upgrade to 5.15.63
      community/jool-modules-lts: rebuild against kernel 5.15.63-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.63-r0
      community/rtpengine-lts: rebuild against kernel 5.15.63-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.63-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.63-r0
      main/zfs-lts: rebuild against kernel 5.15.63-r0
      main/linux-lts: upgrade to 5.15.64
      community/jool-modules-lts: rebuild against kernel 5.15.64-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.64-r0
      community/rtpengine-lts: rebuild against kernel 5.15.64-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.64-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.64-r0
      main/zfs-lts: rebuild against kernel 5.15.64-r0
      main/linux-lts: upgrade to 5.15.67
      community/jool-modules-lts: rebuild against kernel 5.15.67-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.67-r0
      community/rtpengine-lts: rebuild against kernel 5.15.67-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.67-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.67-r0
      main/zfs-lts: rebuild against kernel 5.15.67-r0
      main/linux-lts: upgrade to 5.15.68
      community/jool-modules-lts: rebuild against kernel 5.15.68-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.68-r0
      community/rtpengine-lts: rebuild against kernel 5.15.68-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.68-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.68-r0
      main/zfs-lts: rebuild against kernel 5.15.68-r0
      main/openldap: improve default slapd.ldif
      main/linux-lts: upgrade to 5.15.69
      community/jool-modules-lts: rebuild against kernel 5.15.69-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.69-r0
      community/rtpengine-lts: rebuild against kernel 5.15.69-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.69-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.69-r0
      main/zfs-lts: rebuild against kernel 5.15.69-r0
      main/bind: security upgrade to 9.16.33
      main/linux-lts: upgrade to 5.15.70
      community/jool-modules-lts: rebuild against kernel 5.15.70-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.70-r0
      community/rtpengine-lts: rebuild against kernel 5.15.70-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.70-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.70-r0
      main/zfs-lts: rebuild against kernel 5.15.70-r0
      main/linux-lts: upgrade to 5.15.71
      community/jool-modules-lts: rebuild against kernel 5.15.71-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.71-r0
      community/rtpengine-lts: rebuild against kernel 5.15.71-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.71-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.71-r0
      main/zfs-lts: rebuild against kernel 5.15.71-r0
      main/linux-lts: upgrade to 5.15.72
      community/jool-modules-lts: rebuild against kernel 5.15.72-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.72-r0
      community/rtpengine-lts: rebuild against kernel 5.15.72-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.72-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.72-r0
      main/zfs-lts: rebuild against kernel 5.15.72-r0
      main/linux-lts: upgrade to 5.15.73
      community/jool-modules-lts: rebuild against kernel 5.15.73-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.73-r0
      community/rtpengine-lts: rebuild against kernel 5.15.73-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.73-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.73-r0
      main/zfs-lts: rebuild against kernel 5.15.73-r0
      main/mqtt-exec: upgrade to 0.5
      main/lua-mqtt-publish: upgrade to 0.4
      main/aports-build: fix build error reporting
      main/linux-lts: enable transparent hugepages for virt x86_64
      main/linux-lts: upgrade to 5.15.75
      community/jool-modules-lts: rebuild against kernel 5.15.75-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.75-r0
      community/rtpengine-lts: rebuild against kernel 5.15.75-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.75-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.75-r0
      main/zfs-lts: rebuild against kernel 5.15.75-r0
      main/linux-lts: upgrade to 5.15.76
      community/jool-modules-lts: rebuild against kernel 5.15.76-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.76-r0
      community/rtpengine-lts: rebuild against kernel 5.15.76-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.76-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.76-r0
      main/zfs-lts: rebuild against kernel 5.15.76-r0
      main/linux-rpi: upgrade to 5.15.76
      community/jool-modules-rpi: rebuild against kernel 5.15.76-r0
      main/zfs-rpi: rebuild against kernel 5.15.76-r0
      main/openssl3: upgrade to 3.0.7 (CVE-2022-3602, CVE-2022-3786)
      main/openssl: upgrade to 1.1.1s
      community/sudo: backport fix for CVE-2022-43995
      main/linux-lts: enable CONFIG_IP_VS_MH for virt x86*
      main/linux-lts: upgrade to 5.15.77
      community/jool-modules-lts: rebuild against kernel 5.15.77-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.77-r0
      community/rtpengine-lts: rebuild against kernel 5.15.77-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.77-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.77-r0
      main/zfs-lts: rebuild against kernel 5.15.77-r0
      main/alpine-conf: backport fix for /boot partition size
      main/linux-lts: enable framebuffer console rotation
      main/linux-lts: upgrade to 5.15.78
      community/jool-modules-lts: rebuild against kernel 5.15.78-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.78-r0
      community/rtpengine-lts: rebuild against kernel 5.15.78-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.78-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.78-r0
      main/zfs-lts: rebuild against kernel 5.15.78-r0
      main/linux-rpi: upgrade to 5.15.78
      community/jool-modules-rpi: rebuild against kernel 5.15.78-r0
      main/zfs-rpi: rebuild against kernel 5.15.78-r0
      ===== release 3.16.3 =====

Newbyte (1):
      community/karlender: upgrade to 0.6.1

NickBug (1):
      community/consul-template fix typo error

Nicolas Lorin (1):
      community/ruby-addressable: upgrade to 2.8.1

Oliver Smith (5):
      community/pmbootstrap: upgrade to 1.46.0
      community/pmbootstrap: upgrade to 1.47.0
      community/pmbootstrap: upgrade to 1.47.1
      community/pmbootstrap: upgrade to 1.48.0
      community/pmbootstrap: upgrade to 1.49.0

Pablo Correa Gómez (25):
      community/eog: upgrade to 42.3
      community/evince: upgrade to 42.3
      community/epiphany: upgrade to 42.4
      community/gnome-calculator: upgrade to 42.2
      community/gnome-calendar: upgrade to 42.2
      community/gnome-console: upgrade to 42.2
      community/gnome-shell-extensions: upgrade to 42.3
      community/nautilus: upgrade to 42.2
      community/simple-scan: upgrade to 42.1
      community/gnome-bluetooth: upgrade to 42.2
      community/gnome-desktop: upgrade to 42.4
      community/gnome-initial-setup: upgrade to 42.2
      community/gnome-remote-desktop: upgrade to 42.4
      community/gnome-shell: upgrade to 42.4
      community/mutter: upgrade to 42.4
      community/xdg-desktop-portal-gnome: upgrade to 42.3
      community/gnome-bluetooth: upgrade to 42.4
      community/gnome-control-center: upgrade to 42.4
      community/simple-scan: upgrade to 42.5
      community/yelp: upgrade to 42.2
      community/gnome-desktop: upgrade to 42.5
      community/gnome-remote-desktop: upgrade to 42.5
      community/gnome-shell: upgrade to 42.5
      community/mutter: upgrade to 42.5
      community/yelp-xsl: upgrade to 42.1

Peter Shkenev (1):
      community/virtualbox-guest-additions: security upgrade to 6.1.36

Peter van Dijk (1):
      community/pdns-recursor: upgrade to 4.6.3

Robert Scheck (1):
      main/rsync: upgrade to 3.2.7

Sean McAvoy (1):
      community/jenkins: security upgrade to 2.346.2

Simon Frankenberger (6):
      community/openjdk13: upgrade to 13.0.12
      community/openjdk11: upgrade to 11.0.16.1
      community/openjdk17: upgrade to 17.0.4.1
      community/openjdk17: upgrade to 17.0.5
      community/openjdk11: upgrade to 11.0.17
      community/openjdk11: backport JDK-8267908, fix s390x again

Steve McMaster (1):
      community/suricata: upgrade to 6.0.8

Síle Ekaterin Liszka (1):
      community/nheko: fix CVE-2022-39264

Sören Tempel (2):
      community/go: upgrade to 1.18.7
      main/mosquitto: backport upstream patch for SIGPIPE issue

Tim Stanley (1):
      community/ebusd: upgrade to 22.4

Timo Teräs (2):
      community/openjdk8: security upgrade to 3.24.0
      main/shared-mime-info: remove sync call from trigger

donoban (1):
      community/xorgxrdp: enable x86

macmpi (1):
      community/acpid: upgrade to 2.0.34

omni (22):
      community/tor: upgrade to 0.4.7.10
      community/qutebrowser: depend on py3-pygments
      community/qt5-qtwebengine: chromium security upgrade
      community/dendrite: security upgrade to 0.9.8
      main/expat: security upgrade to 2.4.9
      community/knot-resolver: security upgrade to 5.5.3
      community/consul: security upgrade to 1.12.5
      main/strongswan: add mitigations for CVE-2022-40617
      community/py3-gpep517: backport from edge
      community/pgcli: add missing dependency on py3-pendulum
      community/pgcli: add additional dependencies
      main/linux-lts: upgrade to 5.15.74
      main/dahdi-linux-lts: rebuild against kernel 5.15.74-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.74-r0
      main/zfs-lts: rebuild against kernel 5.15.74-r0
      community/jool-modules-lts: rebuild against kernel 5.15.74-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.74-r0
      community/rtpengine-lts: rebuild against kernel 5.15.74-r0
      main/xen: add mitigations for XSA-412 & XSA-414
      community/qt5-qtwebengine: chromium security upgrade
      community/ansible-core: upgrade to 2.13.6
      main/xen: upgrade to 4.16.2 & add mitigations for XSA-422

psykose (95):
      community/qt5-qtdeclarative: reduce dbg size
      community/qt6-qtbase: reduce dbg size
      community/qt5-qtbase: reduce dbg size
      community/kwin: reduce dbg size
      main/mesa: reduce dbg size
      community/qt5-qtbase: ..but without deleting the commit
      main/libxml2: update secfixes
      main/sqlite: update secfixes
      community/chromium: upgrade to 102.0.5005.173
      main/tzdata: upgrade to 2022b
      main/tzdata: upgrade to 2022c
      main/libxml2: fix CVE-2022-3209
      community/firefox-esr: upgrade to 91.13.0
      community/thunderbird: upgrade to 91.13.0
      main/luajit: remove -msse4.2
      main/mariadb: disable test-aes
      main/mariadb: ..with the correct name
      community/glib-networking: upgrade to 2.72.1
      community/webkit2gtk: upgrade to 2.36.7
      community/webkit2gtk-5.0: upgrade to 2.36.7
      community/vectorscan: reduce -march level
      community/libreswan: fix runscript
      main/curl: patch CVE-2022-32252
      main/curl: correct secfix typo
      main/ssmtp: fix doc install location
      community/go: upgrade to 1.18.6
      testing/*: rebuild with go 1.18.6
      community/*: rebuild with go 1.18.6
      community/go: update secfixes
      community/ginkgo: disable check on s390x
      community/stunnel: fix sh syntax
      main/redis: upgrade to 7.0.5
      community/nodejs-current: upgrade to 18.9.1
      main/rsync: upgrade to 3.2.5
      community/chromium: upgrade to 102.0.5005.182
      community/grpc-java: actually apply the patch
      main/tiff: upgrade to 4.4.0
      community/php81: disable tests for armv7
      main/libxml2: fix secfix typo
      main/dbus: upgrade to 1.14.4
      community/*: rebuild against go 1.18.7
      community/imagemagick: upgrade to 7.1.0.36
      community/imagemagick: upgrade to 7.1.0.37
      community/imagemagick: upgrade to 7.1.0.38
      community/imagemagick: upgrade to 7.1.0.39
      community/imagemagick: upgrade to 7.1.0.40
      community/imagemagick: upgrade to 7.1.0.41
      community/imagemagick: upgrade to 7.1.0.43
      community/imagemagick: upgrade to 7.1.0.44
      community/imagemagick: upgrade to 7.1.0.45
      community/imagemagick: upgrade to 7.1.0.46
      community/imagemagick: upgrade to 7.1.0.47
      community/imagemagick: upgrade to 7.1.0.48
      community/imagemagick: upgrade to 7.1.0.49
      main/postfix: upgrade to 3.7.3
      main/openssl3: security upgrade to 3.0.6
      main/openssl3: downgrade to 3.0.5
      community/netatalk: upgrade to 3.1.13
      main/libxml2: mitigate cves
      main/bcache-tools: add -dbg
      community/poco: use system deps, place them in -dev
      community/py3-django: fix checksums
      main/darkhttpd: upgrade to 1.14
      main/speex: upgrade to 1.2.1
      community/thunderbird: upgrade to 91.13.1
      main/protobuf: rebuild
      main/expat: upgrade to 2.5.0
      main/curl: security fixes
      community/libtorrent-rasterbar: upgrade to 2.0.8
      community/zsnes: try fix build
      community/zsnes: try fix build pt2
      community/zsnes: try fix build pt3
      community/zsnes: fix c++ target name
      main/py3-mako: upgrade to 1.2.1
      community/py3-waitress: upgrade to 2.1.2
      community/py3-waitress: fix provides
      main/tzdata: upgrade to 2022d
      main/tzdata: upgrade to 2022e
      main/tzdata: upgrade to 2022f
      main/perl-datetime-timezone: upgrade to 2.55
      main/perl-datetime-timezone: upgrade to 2.56
      community/sudo: upgrade to 1.9.11_p3
      community/sudo: upgrade to 1.9.12
      main/musl: backport relr patches
      main/pixman: fix CVE-2022-44638
      main/pixman: bump pkgrel
      community/slony1: fix install dir
      main/cyrus-sasl: enable httpform
      community/py3-importlib-metadata: fix version
      main/tzdata: fix zdump
      community/libvirt: fix crash
      main/graphviz: add gd loader
      main/python3: upgrade to 3.10.8
      community/python3-tkinter: upgrade to 3.10.8
      community/xterm: upgrade to 375

ptrcnull (14):
      community/spot: clean up alsa backend references
      main/libnftnl: upgrade to 1.2.3
      community/ruby-net-ldap: upgrade to 0.17.1
      community/yash: upgrade to 2.53
      community/py3-frozendict: upgrade to 2.3.4
      community/stunnel: upgrade to 5.66
      main/py3-mako: upgrade to 1.2.2
      main/py3-mako: upgrade to 1.2.3
      main/perl-datetime-timezone: upgrade to 2.53
      main/perl-datetime-timezone: upgrade to 2.54
      main/py3-tz: upgrade to 2022.4
      community/suricata: upgrade to 6.0.6
      community/suricata: update url
      community/libhtp: upgrade to 0.5.41

wener (2):
      community/grpc-java: enable aarch64
      community/k3s: upgrade to 1.23.12.1



ALPINE LINUX 3.16.1 RELEASED
The Alpine Linux project is pleased to announce the immediate availability of version 3.16.2 of its Alpine Linux operating system.

This release includes various security fixes, including:

busybox CVE-2022-30065
openssl CVE-2022-2097
The full lists of changes can be found in the git log.

GIT SHORTLOG
6543 (2):
      community/synapse: upgrade to 1.61.1
      community/gitea: upgrade to v1.16.9

Andy Postnikov (28):
      community/{php8,php81}: update provider priority
      community/php8-pecl-event: upgrade to 3.0.7
      community/php81-pecl-event: upgrade to 3.0.7
      community/composer: upgrade to 2.3.6
      community/drupal7: upgrade to 7.90
      community/composer: upgrade to 2.3.7
      community/php8-pecl-xdebug: upgrade to 3.1.5
      community/php81-pecl-xdebug: upgrade to 3.1.5
      community/php81: security upgrade to 8.1.7
      community/php8: security upgrade to 8.0.20
      community/php8-pecl-rdkafka: upgrade to 6.0.2
      community/php81-pecl-rdkafka: upgrade to 6.0.2
      main/postgresql14: upgrade to 14.4
      community/php8-pecl-swoole: upgrade to 4.8.10
      community/php81-pecl-swoole: upgrade to 4.8.10
      main/nginx: upgrade modules
      community/njs: upgrade to 0.7.5
      community/php8-pecl-rdkafka: upgrade to 8.0.3
      community/php81-pecl-rdkafka: upgrade to 6.0.3
      community/composer: upgrade to 2.3.8
      community/composer: upgrade to 2.3.9
      community/php8: upgrade to 8.0.21
      community/php81: upgrade to 8.1.8
      community/php81-pecl-swoole: upgrade to 4.8.11
      community/php8-pecl-swoole: upgrade to 4.8.11
      community/composer: upgrade to 2.3.10
      main/openldap: upgrade to 2.6.3
      main/libwebp: upgrade to 1.2.3

Anjandev Momi (1):
      community/nextcloud: upgrade to 24.0.1

Antoine Martin (4):
      community/dotnet6-build: upgrade to 6.0.106
      community/dotnet6-runtime: upgrade to 6.0.6
      community/dotne6-build: upgrade to 6.0.107
      community/dotne6-runtime: upgrade to 6.0.7

Bart Ribbers (7):
      community/kde release service: upgrade to 22.04.1
      community/pmbootstrap: upgrade to 1.44.0
      main/gtk+3.0: fix commands in .post-install
      community/gtk4.0: fix commands in .post-install
      community/kde-release-service: upgrade to 22.04.2
      community/blueman: fix checksums
      community/blueman: fix build

Damian Kurek (1):
      main/gptfdisk: Fix null dereference and enable tests

Dermot Bradley (1):
      [3.16] community/cloud-init: upgrade to 22.2.2

Dominique Martinet (3):
      main/gptfdisk: fix bad uuid generation error
      community/networkmanager: upgrade to 1.38.2
      main/dnsmasq: init: add extra setup command hook

Duncan Bellamy (2):
      community/dovecot-fts-xapian: rebuild against dovecot 2.3.19
      community/ceph: add patch for issue #13892

Francesco Colista (4):
      community/bareos: fix pre-upgrade script
      community/lua-resty-mail: moved from testing
      community/lua-resty-postgres: moved from testing
      community/lua-stacktraceplus: backported from edge

GreyXor (1):
      main/redis: upgrade to 7.0.2

Henrik Riomar (1):
      scripts/mkimg.standard.sh: add linux-firmware-none to the extended iso

J0WI (11):
      main/dpkg: security upgrade to 1.21.8
      community/nss: security upgrade to 3.78.1
      main/cifs-utils: update secfixes
      main/apache2: security upgrade to 2.4.54
      main/pcre2: security upgrade to 10.40
      main/ntfs-3g: security upgrade to 2022.5.17
      main/openssl: security upgrade to 1.1.1p
      community/knot-resolver: upgrade to 5.5.1
      main/openssl: security upgrade to 1.1.1q
      main/openssl: security upgrade to 3.0.5
      main/gnupg: patch CVE-2022-34903

Jacob Panek (2):
      community/caddy: fix listening with TLS
      community/tailscale: add missing ip6tables dependency

Jake Buchholz Göktürk (1):
      community/containerd: [3.16] security upgrade to 1.6.6

Jakob Hauser (1):
      community/xorg-server: upgrade to 21.1.4

Jakub Jirutka (29):
      main/nginx: upgrade to 1.22.0, upgrade modules
      community/njs: upgrade to 0.7.4
      main/libde265: backport CVE patches from upstream
      community/knot-resolver: fix cache error on CoW filesystem
      community/knot-resolver: define error_logger in init script
      community/knot-resolver: rebuild
      community/collectd: backport multiple fixes from upstream
      community/collectd: install headers to allow building out-of-tree plugins
      community/collectd: include *.conf from /etc/collectd.d by default
      main/postgresql-common: use service_set_value and service_get_value
      main/postgresql13: upgrade to 13.7
      community/postgresql12: upgrade to 12.11
      community/bcc: fix broken _tools split - endless sed loop
      community/bcc: don't bundle LLVM into shared library, link dynamically
      community/bpftrace: rebuild
      community/font-noto: fix name of fontconfig configs
      community/font-noto: fix deprecated ERB.new params in noto-meta
      community/font-noto: fix fontconfig configs (again)
      community/avizo: fix missing image on first invocation
      community/swaylock-effects: change upstream and upgrade to 1.6.10
      main/dnsmasq: backport bug fixes from upstream and Fedora
      community/at: import bugfixes from Fedora
      community/at: don't overwrite /var/spool/atd/.SEQ on upgrade
      community/earlyoom: fix typo in init script - don't run as root
      community/earlyoom: fix avoid_cmds, prefer_cmds opts in init script
      community/earlyoom: drop setcap, rather run as root
      community/zzz: upgrade to 0.1.1
      community/xdg-desktop-portal: add missing dependency on cmd:fusermount3
      community/alpine-make-vm-image: upgrade to 0.9.0

Kaarle Ritvanen (2):
      main/awall: upgrade to 1.12.0
      community/py3-django: security upgrade to 3.2.14

Kevin Daudt (3):
      community/salt: upgrade to 3004.2
      community/zabbix: upgrade to 6.0.6
      community/netdata: enable ACLK

Konstantin Kulikov (4):
      community/grafana-frontend: upgrade to 8.5.6
      community/grafana: upgrade to 8.5.6
      community/grafana-frontend: upgrade to 8.5.9
      community/grafana: security upgrade to 8.5.9

Leonardo Arena (4):
      community/nextcloud: inform the user about the correct upgrade path
      community/nextcloud: upgrade to 24.0.2
      community/nextcloud23: upgrade to 23.0.6
      community/nextcloud: fix serverinfo subpkg depends

Luca Weiss (1):
      community/net-cpp: fix issues with new libcurl

Magnus Sandin (1):
      community/pipewire: Fix pipewire-jack to not crash jack clients

Michał Polański (6):
      community/py3-jwt: security upgrade to 2.4.0
      community/intel-media-sdk: upgrade to 22.4.2
      community/coredns: upgrade to 1.9.3
      community/intel-media-sdk: upgrade to 22.4.3
      community/conmon: upgrade to 2.1.2
      community/caddy: upgrade to 2.5.2

Milan P. Stanić (12):
      community/linux-edge: upgrade to 5.18.0
      community/linux-edge: upgrade to 5.18.1
      community/linux-edge: upgrade to 5.18.3
      main/dovecot: bugfix upgrade to 2.3.19.1
      community/linux-edge: upgrade to 5.18.4
      community/linux-edge: upgrade to 5.18.5
      community/linux-edge: upgrade to 5.18.6
      community/linux-edge: upgrade to 5.18.7
      community/linux-edge: upgrade to 5.18.8
      community/linux-edge: upgrade to 5.18.9
      community/linux-edge: upgrade to 5.18.10
      community/linux-edge: upgrade to 5.18.11

Natanael Copa (91):
      community/gnunet-gtk: upgrade to 0.16.0
      main/alpine-baselayout: fix -data to not depend on itself
      main/busybox-initscripts: fix mdev-conf to not depend on itself
      main/ncurses: add secfixes data for CVE-2022-29458
      main/postgresql-common: add secfixes comment for CVE-2019-3466
      main/openldap: add secfixes comment for CVE-2022-29155
      community/exo: upgrade to 4.16.4
      main/linux-lts: enable gpio power reset for armv7 virt kernel
      main/linux-lts: enable libnvdimm and nfit
      main/linux-lts: upgrade to 5.15.43
      main/linux-lts: enable devicetree based probing for 8250 ports
      main/linux-lts: upgrade to 5.15.45
      main/linux-lts: re-enable efi stub
      main/linux-lts: upgrade to 5.15.46
      main/linux-lts: upgrade to 5.15.47
      community/jool-modules-lts: rebuild against kernel 5.15.47-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.47-r0
      community/rtpengine-lts: rebuild against kernel 5.15.47-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.47-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.47-r0
      main/zfs-lts: rebuild against kernel 5.15.47-r0
      main/build-base: set MIT license
      main/linux-lts: upgrade to 5.15.48
      community/jool-modules-lts: rebuild against kernel 5.15.48-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.48-r0
      community/rtpengine-lts: rebuild against kernel 5.15.48-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.48-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.48-r0
      main/zfs-lts: rebuild against kernel 5.15.48-r0
      main/linux-lts: upgrade to 5.15.49
      main/linux-lts: enable BFQ IO scheduler
      main/linux-lts: upgrade to 5.15.50
      community/jool-modules-lts: rebuild against kernel 5.15.50-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.50-r0
      community/rtpengine-lts: rebuild against kernel 5.15.50-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.50-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.50-r0
      main/zfs-lts: rebuild against kernel 5.15.50-r0
      main/linux-lts: upgrade to 5.15.51
      community/jool-modules-lts: rebuild against kernel 5.15.51-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.51-r0
      community/rtpengine-lts: rebuild against kernel 5.15.51-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.51-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.51-r0
      main/zfs-lts: rebuild against kernel 5.15.51-r0
      main/linux-lts: upgrade to 5.15.52
      community/jool-modules-lts: rebuild against kernel 5.15.52-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.52-r0
      community/rtpengine-lts: rebuild against kernel 5.15.52-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.52-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.52-r0
      main/zfs-lts: rebuild against kernel 5.15.52-r0
      main/linux-lts: upgrade to 5.15.53
      community/jool-modules-lts: rebuild against kernel 5.15.53-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.53-r0
      community/rtpengine-lts: rebuild against kernel 5.15.53-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.53-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.53-r0
      main/zfs-lts: rebuild against kernel 5.15.53-r0
      community/mplayer: enable armv7
      main/linux-rpi: upgrade to 5.15.53
      community/jool-modules-rpi: rebuild against kernel 5.15.53-r0
      main/zfs-rpi: rebuild against kernel 5.15.53-r0
      main/linux-lts: upgrade to 5.15.54
      community/jool-modules-lts: rebuild against kernel 5.15.54-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.54-r0
      community/rtpengine-lts: rebuild against kernel 5.15.54-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.54-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.54-r0
      main/zfs-lts: rebuild against kernel 5.15.54-r0
      main/linux-rpi: upgrade to 5.15.54
      community/jool-modules-rpi: rebuild against kernel 5.15.54-r0
      main/zfs-rpi: rebuild against kernel 5.15.54-r0
      main/linux-lts: upgrade to 5.15.55
      community/jool-modules-lts: rebuild against kernel 5.15.55-r0
      community/rtl8821ce-lts: rebuild against kernel 5.15.55-r0
      community/rtpengine-lts: rebuild against kernel 5.15.55-r0
      main/dahdi-linux-lts: rebuild against kernel 5.15.55-r0
      main/xtables-addons-lts: rebuild against kernel 5.15.55-r0
      main/zfs-lts: rebuild against kernel 5.15.55-r0
      main/linux-rpi: upgrade to 5.15.55
      community/jool-modules-rpi: rebuild against kernel 5.15.55-r0
      main/zfs-rpi: rebuild against kernel 5.15.55-r0
      main/alpine-conf: upgrade to 3.14.5
      main/alpine-conf: fix tests over ssh
      main/busybox: add fix for CVE-2022-30065
      main/mkinitfs: upgrade to 3.6.2
      main/busybox-initscripts: refactor tests to kyua
      main/busybox-initscripts: tests for persistent-storage
      main/busybox-initscripts: backwards compat for /dev/usbdisk
      ===== release 3.16.2 =====

Newbyte (8):
      community/gnome-calculator: upgrade to 42.1
      community/karlender: upgrade to 0.4.4
      community/amberol: upgrade to 0.8.0
      community/mozjs91: upgrade to 91.10.0
      community/mozjs91: add icu-data-full to checkdepends
      community/headlines: upgrade to 0.7.1
      community/karlender: upgrade to 0.5.1
      community/karlender: upgrade to 0.6.0

Nicolas Lorin (1):
      community/repmgr: upgrade to 5.3.2

Oliver Smith (3):
      community/pmbootstrap: upgrade to 1.44.1
      community/bemenu: add replaces=sxmo-bemenu
      community/pmbootstrap: upgrade to 1.45.0

Pablo Correa Gómez (9):
      community/gnome-feeds: fix dependencies
      community/gnome-control-center: upgrade to 42.2
      community/gnome-control-center: add patch to fix change password dialog
      community/gnome-remote-desktop: upgrade to 42.2
      community/gnome-remote-desktop: add lang subpackage
      community/gnome-remote-desktop: update url
      main/gtk+2.0: fix commands in .post-install
      community/chatty: upgrade to 0.6.7
      community/gnome-control-center: upgrade to 42.3

Peter Shkenev (1):
      [3.16] community/gajim: add missing dependency

Robert Scheck (1):
      community/signify: enable on armhf

Simon Frankenberger (1):
      main/gnupg: fix importing ed25519 keys with leading zero bit (MPI key)

Stephen Abbene (1):
      main/alpine-baselayout: fix pre-upgrade erroneously detecting symlinks as dirs

Sören Tempel (2):
      main/busybox: fix yet another use-after-free in BusyBox ash
      main/mkinitfs: provide initramfs-generator

Thomas Liske (1):
      community/lldpd: upgrade to 1.0.14

Wesley van Tilburg (6):
      community/minify: upgrade to 2.11.5
      community/minify: upgrade to 2.11.7
      community/minify: upgrade to 2.11.9
      community/minify: upgrade to 2.11.10
      community/minify: upgrade to 2.11.11, add options=net
      community/minify: upgrade to 2.11.12

Will Sinatra (1):
      community/sbcl: fix dynamic space and sb:thread

donoban (2):
      community/bubblejail: upgrade to 0.6.1
      community/bubblejail: upgrade to 0.6.2

knuxify (2):
      community/gnome-feeds: re-add py3-syndom dependency
      community/blueman: upgrade to 2.2.5

macmpi (3):
      community/bluez-alsa: upgrade to 4.0.0
      main/linux-firmware: update pi brcmfmac43436 files to 1:20210315-3+rpt6 release
      community/bluez-alsa: build all utilities into a utils sub-package

omni (12):
      community/qt5-qtwebengine: chromium security upgrade
      main/xen: add mitigations for XSA-401 & XSA-402
      community/tor: security upgrade to 0.4.7.8
      main/xen: add mitigations for XSA-404
      main/linux-lts: backport export mmu_feature_keys as non-GPL
      main/zfs: upgrade to 2.1.5
      main/zfs-lts: upgrade to 2.1.5
      main/xen: add mitigations for XSA-403
      community/libvirt: rebuild against xen 4.16.1-r3
      community/py3-mistune: security upgrade to 2.0.3
      main/xen: add mitigations for XSA-407
      community/py3-mistune: upgrade to 2.0.4

prspkt (1):
      community/wavpack: security upgrade to 5.5.0

psykose (77):
      community/qbittorrent: upgrade to 4.4.3
      community/glib-networking: revert back to gnutls
      community/prosody: add icu-data-full to depends
      community/prosody: move icu-data-full to top-level
      community/libkgapi: disable failing tests
      main/cairo: actually apply inf-loop patch
      community/openbox: make autostart py3 compatible
      main/libidn2: fix utils path
      community/tectonic: add icu-data-full dependency
      community/vectorscan: remove march=native, use ninja
      community/qbittorrent: upgrade to 4.4.3.1
      main/cups: upgrade to 2.4.2
      community/chromium: upgrade to 102.0.5005.61
      community/chromium: use bundled desktop file, install metadata
      community/bloaty: move .so to main package
      main/alpine-conf: upgrade to 3.14.2
      main/gnutls: upgrade to 3.7.6
      community/qt6-qt5compat: add icu-data-full
      main/apr: fix CVE-2021-35940
      community/qbittorrent: fix rss on qt 6.3.0
      community/firefox-esr: upgrade to 91.10.0
      community/firefox: upgrade to 101.0
      community/cbindgen: upgrade to 0.23.0
      community/thunderbird: upgrade to 91.10.0
      community/wlroots: allow replace for sxmo-wlroots
      community/ffnvcodec-headers: new aport
      main/logrotate: fix CVE-2022-1348
      community/evolution-data-server: upgrade to 3.44.2
      community/evolution: upgrade to 3.44.2
      community/evolution-ews: upgrade to 3.44.2
      community/py3-ipykernel: amend dependencies
      community/quassel: don't depend on self top-level
      community/blender: don't depend on blender-shared on self
      community/py3-readability-lxml: remove !py3-readability reference
      main/gnupg: remove !gnupg reference
      community/modemmanager: make libmm not depend on itself
      community/bareos: make storage-daemon not depend on pkgname
      community/dotnet6-runtime: make host not depend on hostxfr
      community/quassel: split -libs
      community/blender: actually remove circular dep on -shared
      community/bareos: split -libs
      main/gnupg: remove more circular depends
      community/containerd: correct secfix version
      community/firefox: upgrade to 101.0.1
      main/gstreamer: upgrade to 1.20.3
      main/gst-plugins-base: upgrade to 1.20.3
      community/py3-gst: upgrade to 1.20.3
      community/gst-plugins-ugly: upgrade to 1.20.3
      community/gst-libav: upgrade to 1.20.3
      community/gst-plugins-bad: upgrade to 1.20.3
      community/gst-plugins-good: upgrade to 1.20.3
      community/gst-editing-services: upgrade to 1.20.3
      community/audacious: add qt5-qtsvg to depends
      main/logrotate: fix permissions of logrotate status
      community/gitea: don't run passwd -u without fresh user creation
      community/networkmanager: add -dbg
      main/linux-firmware: add brcm-43436 firmware
      community/firefox-esr: upgrade to 91.11.0
      community/thunderbird: upgrade to 91.11.0
      main/curl: add fixes for cves
      community/keepalived: add support for SNMP RFC MIBs
      community/py3-ujson: upgrade to 5.4.0
      community/webkit2gtk-5.0: upgrade to 2.36.4
      community/webkit2gtk: upgrade to 2.36.4
      community/py3-scikit-learn: add missing dependency
      community/xscreensaver: upgrade to 6.04
      main/binutils: backport fix for -Os on ppc64le
      community/xorg-server: fix CVE-2022-2319 and CVE-2022-2320
      community/xorg-server: rename patches
      main/mbedtls: upgrade to 2.28.1
      testing/gn: upgrade to 0_git20220608
      community/gn: move from testing
      community/chromium: upgrade to 102.0.5005.158
      main/git: upgrade to 2.36.2
      main/freetype: update cves
      main/rsync: fix rrsync dependency on python3
      main/dhcpcd: fix openrc management

ptrcnull (12):
      community/zabbix: upgrade to 6.0.5
      community/labwc: add missing xwayland dependency
      community/xf86-video-qxl: replace get_boolean_option patch
      main/libid3tag: upgrade to 0.16.2
      community/easytag: rebuild against libid3tag-0.16.2-r0
      community/libmp3splt: rebuild against libid3tag-0.16.2-r0
      community/minidlna: rebuild against libid3tag-0.16.2-r0
      community/mpd: rebuild against libid3tag-0.16.2-r0
      community/sox: rebuild against libid3tag-0.16.2-r0
      community/tenacity: rebuild against libid3tag-0.16.2-r0
      main/imlib2: rebuild against libid3tag-0.16.2-r0
      main/net-snmp: upgrade to 5.9.3

rubicon (3):
      community/sbcl: upgrade to 2.2.5
      community/ecl: fix specification of integer suffixes
      main/perl-lwp-protocol-https: add install_if for perl-app-cpanminus

vin01 (1):
      community/salt: remove stale patch for python3.10 compatibility

ALPINE LINUX 3.16.0 RELEASED
We are pleased to announce the release of Alpine Linux 3.16.2, the first in the v3.16 stable series.

HIGHLIGHTS
Various improvements in the setup scripts:
Better support for NVMe
Administrator user creation
Possibility to add SSH keys
New setup-desktop script for easy install of desktop environment
Go 1.18
LLVM 13
Node.js (current) 18.2
Ruby 3.1
Rust 1.60
GNOME 42
KDE Plasma 5.24 / KDE Applications 22.04 / Plasma Mobile Gear 22.04
Python 3.10
PHP 8.1
R 4.2
Xen 4.16
Podman 4.0
SIGNIFICANT CHANGES
sudo has been moved to community repository, which means that only latest stable release branch will get security updates in the future. Suggested replacement is doas and doas-sudo-shim.
UPGRADE NOTES
As always, make sure to use apk upgrade --available when switching between major versions.
Both shadow-login and util-linux-login provides login-utils with this release. The preferred implementation is from util-linux.
NetworkManager plugins have moved to subpackages and are no longer installed by default. Users may need install plugins to not lose network connectivity.
The ICU data has been split into icu-data-en (default) and icu-data-full packages. Users may need to install icu-data-full for non-English locales or legacy charset converters support.
DEPRECATION NOTES
php7 was removed.
python2 was removed.
CHANGES
The full list of changes can be found in the wiki, git log and bug tracker.

CREDITS
Thanks to everyone sending patches, bug reports, new and updated aports, and to everyone helping with writing documentation, maintaining the infrastructure, or contributing in any other way!

Thanks to GIGABYTE, Linode, Fastly, IBM, Equinix Metal, vpsFree and RapidSwitch for providing us with hardware and hosting.

APORTS COMMIT CONTRIBUTORS
6543
A. Wilcox
Adam Jensen
Adam Plumb
Aiden Grossman
Aleks Bunin
Aleksei Nikiforov
Alex Denes
Alex Dowad
Alex McGrath
Alex Xu (Hello71)
Alex Yam
Alexander Brzoska
Alexey Andreyev
Alexey Yerin
Alisa
Alistair Francis
Andreas Schneider
Andrei Jiroh Eugenio Halili
Andrew Harris
André Klitzing
Andrés Maldonado
Andy Hawkins
Andy Postnikov
Anjandev Momi
Antoine Fontaine
Antoine Martin
Antoni Aloy Torrens
Apo Apangona
Ariadne Conill
Arnavion
Bart Ribbers
Bertrand Lupart
Bill Sprinters
Bobby The Builder
Boris Faure
Bradford D. Boyle
Caleb Connolly
Carlgo11
Carlo Landmeter
Chris Kruger
Chris Vittal
Christian Franke
Clayton Craft
Cormac Stephenson
Cory Sanin
Curt Tilmes
Dan Theisen
Daniel Gray
Daniel Kolesa
Daniel Néri
Daniil Nemtsev
David A. Hannasch
David Demelier
David Florness
Dekedro
Dermot Bradley
Dhruvin Gandhi
Dmitry Kruchko
Dmitry Romanenko
Dmitry Zakharchenko
Dominik Schulz
Dominika Liberda
Dominique Martinet
Drew DeVault
Duncan Bellamy
Dylan Van Assche
Díaz Urbaneja Víctor Diego Alejandro
Edd Salkield
Eirik Furuseth
Elaina Thompson
Eloi Torrents
Er2
Erik Larsson
Evgeny Grin
Fabian Affolter
Fernando Oleo Blanco
FollieHiyuki
Francesco Camuffo
Francesco Colista
Frank Oltmanns
Galen Abell
Gavin Henry
Gennady Feldman
Geod24
Glenn Strauss
GreyXor
Grigory Kirillov
Guilherme Felipe da Silva
Guillaume Quintard
Guy Godfroy
Hakan Erduman
Hazem
Henrik Grimler
Henrik Riomar
Hiroshi Kajisha
Holger Jaekel
Hugo Wang
Humm
Ian Bashford
Iztok Fister Jr
J0WI
Jake Buchholz Göktürk
Jakob Hauser
Jakub Jirutka
Jakub Panek
Jason A. Donenfeld
Jesse Chan
Jinming Wu, Patrick
Johannes Heimansberg
Jonas
Joonas Kuorilehto
Jordan Christiansen
Jost Brandstetter
JuniorJPDJ
Justin
Justin Berthault
KILLERTKK
Kaarle Ritvanen
Kate
Kate Deplaix
Kevin Daudt
Kevin Thomas
Kevin Wang
Klaus Frank
Konstantin Kulikov
Krystian Chachuła
Laszlo Soos
Lauren N. Liberda
Laurent Bercot
Leo
Leon Marz
Leon ROUX
Leonardo Arena
Lin, Meng-Bo
Linux User
Lova Widmark
Luca Weiss
Lucas Ramage
Lucidiot
Maarten van Gompel
Magnus Sandin
Malte Voos
Marcelo Duarte
Marco Martinelli
Marco Schröder
Marian Buschsieweke
Marin Purgar
Mark Pashmfouroush
Martijn Braam
Martin Hasoň
Martin Kühl
Marvin Preuss
Mathieu Mirmont
Matthew T Hoare
MaxPeal
Maxim Karasev
Michael Lyngbol
Michael Pirogov
Michael Truog
Michal Jirku
Michał Adamski
Michał Polański
Mike Banon
Mike Crute
Milan P. Stanić
Miles Alan
Minecrell
Misthios
Mogens Jensen
Natanael Copa
Nathan
Nathan Angelacos
Nero
Newbyte
Nick Hanley
Nico de Haer
Nicolas Lorin
Nilushan Costa
Noel Kuntze
Nulo
Oleg Titov
Oliver Smith
Olliver Schinagl
Pablo Correa Gómez
Patrick Gansterer
Paul Bredbury
Paul Spooren
Pedro Lucas Porcellis
Peter Shkenev
Peter Spiess-Knafl
Peter van Dijk
Petr Vorel
Philipp Arras
Piper McCorkle
Pranjal Kole
QShen3
R4SAS
Ralf Rachinger
Raymond Hackley
Rob Blanckaert
Robert Günzler
Robert Schütz
Roel Standaert
Rosen Penev
Roshless
S.M Mukarram Nainar
Sadie Powell
Saijin-Naib
Sashanoraa
Scott Robinson
Sean McAvoy
Sebastian
Shawn Rose
Sheila Aman
Simon Frankenberger
Simon Rupf
Simon Ser
Simon Zeni
Siva Mahadevan
Sodface
Stacy Harper
Steffen Nurpmeso
Steve McMaster
Steven Honson
Stéphane Alnet
Sven Wick
Sylvain Prat
Síle Ekaterin Liszka
Sören Tempel
Taner Tas
Thiago Perrotta
Thomas Deutsch
Thomas Kienlen
Thomas Liske
Tim Stanley
Timo Brasz
Timo Teräs
Timothee LF
Timothy Legge
Tom Lebreux
Tom Tsagk
Tuan Hoang
Umar Getagazov
Waweic
Weilu Jia
Wesley van Tilburg
Will Sinatra
Wolf
Xe
Yagnesh Mistry
Zach DeCook
Zhuo FENG
alealexpro100
ayakael
chenrui
crapStone
donoban
fanquake
firefly-cpp
guddaff
j.r
jakovrr
jvoisin
kedap
knuxify
kpcyrd
krystianch
kt programs
ktprograms
leso-kn
lonjil
macmpi
mcha
messense
mio
mochaaP
mterron
nibon7
nick black
nilushancosta
omni
p3lim
prspkt
psykose
ptrcnull
quietsy
rubicon
sergiotarxz
shum
techknowlogick
tiotags
wener
xrs
Óliver García
博麗霊夢

ALPINE LINUX 3.15.0 RELEASED
We are pleased to announce the release of Alpine Linux 3.15.0, the first in the v3.15 stable series.

HIGHLIGHTS
Linux kernels 5.15 (LTS)
llvm 12
nodejs 16.13 (LTS) / nodejs-current 17.0
postgresql 14
openldap 2.6
ruby 3.0
rust 1.56
openjdk 17
kea 2.0
xorg-server 21.1
GNOME 41
KDE Plasma 5.23 / KDE Applications 21.08 / Plasma Mobile Gear 21.10
Support for disk encryption in installer
Support for out-of-tree kernel modules via AKMS (inspired by DKMS)
Initial support for UEFI Secure Boot on x86_64
SIGNIFICANT CHANGES
Kernel modules are now compressed with gzip.
Framebuffer drivers have been disabled in kernel and replaced by simpledrm.
qt5-qtwebkit and related packages have been removed due to lack of upstream support.
The MIPS64 port is discontinued. The architecture is EOL and no new releases will be made. See TSC#27.


UPGRADE NOTES
As always, make sure to use apk upgrade --available when switching between major versions.
New 4096 bit RSA keys are now used for package signatures. Make sure alpine-keys>=2.4.0-r0 is installed on your system before upgrading.
Multiple major versions of PostreSQL can now be installed in parallel to facilitate upgrades. See the PostgreSQL upgrade notes for more details.
radvd no longer enables forwarding for IPv6. If still required, make sure net.ipv6.conf.all.forwarding is enabled.
Several ruby packages have been moved to dedicated aports, and others have merged into a single package. See the wiki for details.


DEPRECATION NOTES
sudo will be moved to community in Alpine Linux 3.16. The suggested replacement is doas, which is available in main. See TSC#1
php7 is being phased out, as the last release, 7.4 will have only 1 year of security support left.



ALPINE LINUX 3.14.8 RELEASED
The Alpine Linux project is pleased to announce the immediate availability of version 3.14.8 of its Alpine Linux operating system.

This release includes fixes for openssl CVE-2021-3711 and CVE-2021-3712.

The full lists of changes can be found in the git log.

GIT SHORTLOG
6543 (1):
      community/gitea: upgrade to 1.14.6

Andy Postnikov (10):
      main/postgresql: security upgrade to 13.4 (CVE-2021-3677)
      community/composer: upgrade to 2.1.6
      community/icinga2: security upgrade to 2.12.6 (CVE-2021-37698)
      main/pgpool: upgrade to 4.2.4
      community/stunnel: upgrade to 5.60
      community/php8: improve, build php only twice: apache2+cgi and the rest
      community/php8: security upgrade to 8.0.10
      main/nodejs: security upgrade to 14.17.5
      community/php7: security upgrade to 7.4.23
      community/php7: improve build

Anjandev Momi (1):
      community/prosody: upgrade to 0.11.10

Ariadne Conill (4):
      main/gpsd: move back from community
      main/ruby: add CVE-2021-31799 to secfixes
      main/asterisk: add mitigation for CVE-2021-32558
      main/libspf2: add mitigation for CVE-2021-20314

Bart Ribbers (8):
      community/plasma: upgrade to 5.22.4
      community/plasma-workspace: rebuild against gpsd 3.23
      community/marble: rebuild against gpsd 3.23
      community/stellarium: rebuild against gpsd 3.23 and modernize
      community/kasts: add missing dep on qt5-qtbase-sqlite
      community/amazfish: upgrade to 2.0.2
      community/sddm: improve init script
      community/plasma-phone-components: backport fix for screenshots

Daniel Néri (1):
      main/unbound: upgrade to 1.13.2

Duncan Bellamy (1):
      community/dovecot-fts-xapian: upgrade to 1.4.12

J0WI (11):
      community/apache-ant: security upgrade to 1.10.11
      main/ruby: security upgrade to 2.7.4
      community/firefox-esr: security upgrade to 78.12.0
      community/openjdk7: upgrade to 2.6.25
      community/openjdk7: security upgrade to 7.301.2.6.26
      main/mariadb: security upgrade to 10.5.12
      community/rust: upgrade to 1.52.1
      community/rust: patch CVE-2021-29922
      community/mozjs78: security upgrade to 78.13.0
      community/tor: security upgrade to 0.4.5.10
      main/openssl: security upgrade to 1.1.1l

Kevin Daudt (18):
      community/uglifycss: remove node_modules/root folder
      community/uglify-js: remove node_modules/root folder
      main/c-ares: security upgrade to 1.17.2 (CVE-2021-3672)
      community/bupstash: rebuild to mitigate CVE-2021-29922
      community/corrosion: rebuild to mitigate CVE-2021-29922
      community/git-metafile: rebuild to mitigate CVE-2021-29922
      community/librsvg: rebuild to mitigate CVE-2021-29922
      community/mozjs78: rebuild to mitigate CVE-2021-29922
      community/newsflash: rebuild to mitigate CVE-2021-29922
      community/squeekboard: rebuild to mitigate CVE-2021-29922
      community/suricata: rebuild to mitigate CVE-2021-29922
      community/tokei: rebuild to mitigate CVE-2021-29922
      community/alacritty: rebuild to mitigate CVE-2021-29922
      community/salt: upgrade to 3003.2
      main/bind: security upgrade to 9.16.20 (CVE-2021-25218)
      main/bind: patch map format
      community/chezmoi: upgrade to 2.0.16
      community/libssh: security upgrade to 0.9.6 (CVE-2021-3634)

Leo (4):
      community/fetchmail: security upgrade to 6.4.20
      community/gpsd: upgrade to 3.23
      main/grep: upgrade to 3.7
      community/wireshark: upgrade to 3.4.8

Leonardo Arena (3):
      community/nextcloud: upgrade to 21.0.4
      community/nextcloud20: upgrade to 20.0.12
      community/zabbix: upgrade to 5.4.3 and fix proc.num support in Agent 2

Michał Polański (2):
      community/hcloud: upgrade to 1.26.1
      community/fuse-overlayfs: upgrade to 1.7.1

Milan P. Stanić (2):
      main/haproxy: security upgrade to 2.4.3
      main/haproxy: don't override CFLAGS in make

Natanael Copa (33):
      community/go: upgrade to 1.16.7 (CVE-2021-36221)
      main/linux-lts: upgrade to 5.10.59
      community/jool-modules-lts: rebuild against kernel 5.10.59-r0
      community/rtl8821ce-lts: rebuild against kernel 5.10.59-r0
      community/rtpengine-lts: rebuild against kernel 5.10.59-r0
      main/dahdi-linux-lts: rebuild against kernel 5.10.59-r0
      main/xtables-addons-lts: rebuild against kernel 5.10.59-r0
      main/zfs-lts: rebuild against kernel 5.10.59-r0
      main/busybox-initscripts: create /dev/virtio-ports symlinks
      main/busybox-initscripts: fix mdev.conf to work with mdev -s
      main/linux-rpi: upgrade to 5.10.60
      community/jool-modules-rpi: rebuild against kernel 5.10.60-r0
      main/zfs-rpi: rebuild against kernel 5.10.60-r0
      main/linux-lts: upgrade to 5.10.60
      community/jool-modules-lts: rebuild against kernel 5.10.60-r0
      community/rtl8821ce-lts: rebuild against kernel 5.10.60-r0
      community/rtpengine-lts: rebuild against kernel 5.10.60-r0
      main/dahdi-linux-lts: rebuild against kernel 5.10.60-r0
      main/xtables-addons-lts: rebuild against kernel 5.10.60-r0
      main/zfs-lts: rebuild against kernel 5.10.60-r0
      main/linux-rpi: upgrade to 5.10.61
      community/jool-modules-rpi: rebuild against kernel 5.10.61-r0
      main/zfs-rpi: rebuild against kernel 5.10.61-r0
      main/linux-lts: upgrade to 5.10.61
      community/jool-modules-lts: rebuild against kernel 5.10.61-r0
      community/rtl8821ce-lts: rebuild against kernel 5.10.61-r0
      community/rtpengine-lts: rebuild against kernel 5.10.61-r0
      main/dahdi-linux-lts: rebuild against kernel 5.10.61-r0
      main/xtables-addons-lts: rebuild against kernel 5.10.61-r0
      main/zfs-lts: rebuild against kernel 5.10.61-r0
      scripts/mkimg.base.sh: include gnu wget
      main/raspberrypi-bootloader: upgrade to 1.20210805
      ===== release 3.14.8 =====

Oliver Smith (1):
      community/pmbootstrap: upgrade to 1.36.0

Thomas Liske (3):
      community/py3-pyroute2: fix empty ipset content
      community/frr: fix reload script and add checkpath to initd
      community/ifstate: upgrade to 1.5.5

wener (1):
      community/tinc-pre: upgrade to 1.1pre18

ALPINE LINUX 3.14.1 RELEASED
The Alpine Linux project is pleased to announce the immediate availability of version 3.14.1 of its Alpine Linux operating system.

This release includes a fix for apk-tools CVE-2021-36159.

The full lists of changes can be found in the git log.

GIT SHORTLOG
6543 (1):
      community/gitea: upgrade to 1.14.3

Andy Postnikov (16):
      community/php7-pecl-imagick: upgrade to 3.5.0
      community/php8-pecl-imagick: upgrade to 3.5.0
      community/php7-pecl-xhprof: upgrade to 2.3.3
      community/php8-pecl-xhprof: upgrade to 2.3.3
      community/php8: security upgrade to 8.0.8 - CVE-2021-21705
      community/php7: security upgrade to 7.4.21 - CVE-2021-21705
      community/php7-pecl-ast: upgrade to 1.0.13
      community/php8-pecl-ast: upgrade to 1.0.13
      community/php7-pecl-mongodb: upgrade to 1.10.0
      community/php8-pecl-mongodb: upgrade to 1.10.0
      community/drupal7: security upgrade to 7.82 - CVE-2021-32610
      community/php7-pecl-igbinary: upgrade to 3.2.4
      community/php8-pecl-igbinary: upgrade to 3.2.4
      community/nodejs-current: security upgrade to 16.6.0
      community/php7: upgrade to 7.4.22
      community/php8: upgrade to 8.0.9

Ariadne Conill (28):
      main/rssh: add mitigations for CVE-2019-3463 and CVE-2019-1000018, secfixes data for CVE-2019-3464
      main/nikto: add mitigation for CVE-2018-11652
      main/avahi: add mitigation for CVE-2021-3468
      main/patch: add mitigation for CVE-2019-20633
      main/unzip: add mitigation for CVE-2018-18384 (incomplete fix of CVE-2014-9913)
      main/{bind,dhcp}: fix secfixes data for CVE-2019-6470
      community/quassel: add mitigation for CVE-2021-34825
      community/gdnsd: security upgrade to 2.4.3 (CVE-2019-13952)
      main/luajit: disable some tests on mips64
      main/luajit: fix testsuite paths for mips64 case
      community/notcurses: skip tests on mips64, slow builder
      community/opendmarc: add mitigation for CVE-2021-34555
      main/libretls: downgrade libtls SOVERSION to allow coexistence with community/libressl
      main/libretls: add so:libtls.so.20 provides for transitional period
      main: chase libretls SOVERSION change
      community/codemadness-frontends: chase libretls SOVERSION change
      main/zstd: disable tests on 32-bit arm due to issues caused by having 160 threads
      community/csync2: add mitigations for CVE-2019-15522 and CVE-2019-15523
      community/applet-window-buttons: block on mips64
      community/xrdp: update secfixes data
      community/libvterm: add mitigation for CVE-2018-20786
      main/avahi: add mitigation for CVE-2021-36217
      community/hdf5: fix secfixes
      main/nodejs: security upgrade to 14.17.3 (CVE-2021-22918)
      main/aspell: add mitigation for CVE-2019-25051 / OSV-2020-521
      community/libmad: fix secfixes data to include CVE-2018-7263
      community/openvswitch: add mitigation for CVE-2021-36980
      community/djvulibre: add mitigations for CVE-2021-3500, CVE-2021-32490, CVE-2021-32491, CVE-2021-32492, CVE-2021-32493

Bart Ribbers (20):
      community/py3-tinydb: upgrade to 4.4.0 and modernize
      community/plasma: upgrade to 5.22.2.1
      community/plasma-desktop: disable on ppc64le
      community/purpose: disable on ppc64le
      community/plasma-browser-integration: disable on ppc64le
      community/plasma-desktop: actually disable on ppc64le
      community/applet-window-buttons: new aport
      community/mauikit: depend on applet-window-buttons
      community/mauikit-texteditor: new aport
      community/nota: depend on mauikit-texteditor
      community/buho: add dep on mauikit-texteditor
      community/buho: bump pkgrel
      community/xwayland: add missing replaces on xorg-server-xwayland
      community/wlroots0.12: add missing replaces on wlroots
      community/discover: disable KCM
      community/osmscout-server: upgrade to 2.0.3
      community/osmscout-server: install proper config version
      community/plasmatube: upgrade to 0_git20210709
      community/plasmatube: upgrade to 0_git20210718
      community/plasmatube: upgrade to 0_git20210719

Carlo Landmeter (2):
      main/libretls: fix boostrap build
      community/vectorscan: add debug symbols package

Clayton Craft (1):
      community/gnome-shell: drop dependency on nm-applet

Devin Lin (2):
      community/kweathercore: new aport
      community/kweather: upgrade to 21.06

Duncan Bellamy (6):
      community/dovecot-fts-xapian: upgrade to 1.4.10 rebuild against new dovecot
      community/dovecot-fts-xapian: upgrade to 1.4.11
      community/rspamd: use luajit for all arches * add lpeg patch * fixes #12822
      community/ceph: upgrade to 16.2.5
      community/suricata: upgrade to 6.0.3
      community/libhtp: upgrade to 0.5.38

Francesco Colista (4):
      community/bareos: remove py3-selenium dep from webui subpackage
      community/sngrep: enable eep support
      community/sngrep: disable test-003
      main/sofia-sip: upgrade to 1.13.4

Henrik Riomar (1):
      main/rsyslog: load custom config before standard rules

Holger Jaekel (2):
      community/gdal: upgrade to 3.2.3
      community/hdf5: upgrade to 1.12.1

J0WI (11):
      main/mariadb: security upgrade to 10.5.11
      community/firefox: upgrade to 89.0.1
      main/nspr: upgrade to 4.31
      community/mozjs78: security upgrade to 78.12.0
      main/varnish: security upgrade to 6.6.1
      main/curl: security upgrade to 7.78.0
      main/redis: security upgrade to 6.2.5
      main/krb5: security upgrade to 1.18.4
      community/miniupnpd: update secfixes
      community/exiv2: security upgrade to 0.27.4
      main/libretls: upgrade to 3.3.3p1

Jakub Jirutka (12):
      community/yamllint: upgrade to 1.26.1
      community/njs: upgrade to 0.5.3
      community/cesnet-tcs-cli: upgrade to 0.4.0
      community/libstemmer: remove duplicate
      main/fail2ban: fix tests and re-enable for all arches
      main/fail2ban: move tests to -test subpackage
      main/fail2ban: remove path configs for other distros
      main/fail2ban: skip failing DNSUtilsNetworkTests.testFQDN
      main/dhcpcd: upgrade to 8.1.9
      community/ruby-ffi: upgrade to 1.15.3
      community/git-metafile: upgrade to 0.2.1
      */linux-*: fix perms of kernel.release file to 644

Kaarle Ritvanen (1):
      community/py3-django: security upgrade to 3.1.13

Kevin Daudt (4):
      main/openssh: reset dependencies for client-common
      community/java-jffi: disable on mips64 due to missing java
      community/zabbix: upgrade to 5.4.2
      main/rsync: prevent aports version being reported

Leo (16):
      community/synapse: upgrade to 1.36.0
      community/skopeo: depend on containers-common during runtime
      community/vault: remove duplicate CVE value
      *: remove duplicate CVE values
      community/synapse: upgrade to 1.37.0
      community/synapse: upgrade to 1.37.1
      community/xrdp: generate key and certificate at runtime
      community/py3-rich: upgrade to 10.5.0
      community/gnome-authenticator: depend on py3-setuptools at runtime
      community/ntpsec: security upgrade to 1.2.1
      main/glib: upgrade to 2.68.3
      community/wireshark: upgrade to 3.4.7
      main/gummiboot: move from unmaintained
      main/gummiboot: fix build with latest GNU-EFI
      main/gummiboot: split EFISTUB into gummiboot-efistub
      community/go: security upgrade to 1.16.6

Leonardo Arena (3):
      main/open-iscsi: fix path of iscsi-name in init script
      community/nextcloud: upgrade to 21.0.3
      community/nextcloud20: upgrade to 20.0.11

Marian Buschsieweke (1):
      community/texlive: fix trigger script

Martijn Braam (1):
      community/pmbootstrap: upgrade to 1.34.0

Martin Hasoň (2):
      main/py3-pillow: upgrade to 8.2.0
      community/py3-reportlab: upgrade to 3.5.68

Martin Kaesberger (2):
      community/chromium: upgrade to 91.0.4472.114
      community/chromium: upgrade to 91.0.4472.164

Michał Polański (25):
      main/nodejs: upgrade to 14.17.1
      community/lagrange: upgrade to 1.5.2
      community/caddy: upgrade to 2.4.3
      community/libslirp: upgrade to 4.6.1
      community/hcloud: upgrade to 1.24.0
      community/py3-faker: upgrade to 8.8.1
      community/podman: fix panic when cgroup filesystem is not mounted
      community/fuse-overlayfs: upgrade to 1.6
      community/podman: upgrade to 3.2.2
      community/containers-common: upgrade to 0.38.11
      community/skopeo: upgrade to 1.3.1
      community/buildah: upgrade to 1.21.2
      community/buildah: add dependency on crun
      community/wdisplays: change upstream
      community/wdisplays: upgrade to 1.1
      community/hcloud: upgrade to 1.25.0
      community/hcloud: upgrade to 1.25.1
      community/buildah: upgrade to 1.21.3
      community/podman: upgrade to 3.2.3
      community/buildah: upgrade to 1.21.4
      community/crun: upgrade to 0.21
      main/nodejs: security upgrade to 14.17.4
      community/fuse-overlayfs: upgrade to 1.7
      community/slirp4netns: upgrade to 1.1.12
      community/hcloud: upgrade to 1.26.0

Milan P. Stanić (5):
      main/haproxy: upgrade to 2.4.1
      community/clamav: upgrade to 0.103.3
      main/dovecot: security upgrade to 2.3.15
      main/postfix: upgrade to 3.6.2
      main/haproxy: upgrade to 2.4.2

Natanael Copa (50):
      scripts/mkimg.base.sh: add dhcpcd to base
      community/py3-gevent: upgrade to 21.1.2
      main/kamailio: backport mohqueue fixes from upstream
      community/containerd: security upgrade to 1.5.4 (CVE-2021-32760)
      main/rsync: backport fix for --delay-updates
      main/linux-lts: enable HIGHMEM and LPAE for armv7 -virt
      main/linux-lts: upgrade to 5.10.44
      main/linux-lts: upgrade to 5.10.45
      main/linux-lts: upgrade to 5.10.46
      main/linux-lts: upgrade to 5.10.47
      main/linux-lts: upgrade to 5.10.48
      main/linux-lts: upgrade to 5.10.49
      main/linux-lts: upgrade to 5.10.50
      main/linux-lts: upgrade to 5.10.51
      main/linux-lts: upgrade to 5.10.52
      main/linux-lts: upgrade to 5.10.53
      main/linux-lts: upgrade to 5.10.54
      main/linux-lts: upgrade to 5.10.55
      community/jool-modules-lts: rebuild against kernel 5.10.55-r0
      community/rtl8821ce-lts: rebuild against kernel 5.10.55-r0
      community/rtpengine-lts: rebuild against kernel 5.10.55-r0
      main/dahdi-linux-lts: rebuild against kernel 5.10.55-r0
      main/xtables-addons-lts: rebuild against kernel 5.10.55-r0
      main/zfs-lts: rebuild against kernel 5.10.55-r0
      main/linux-rpi: upgrade to 5.10.44
      main/linux-rpi: upgrade to 5.10.45
      main/linux-rpi: upgrade to 5.10.46
      main/linux-rpi: upgrade to 5.10.49
      main/linux-rpi: upgrade to 5.10.50
      main/linux-rpi: upgrade to 5.10.51
      main/linux-rpi: upgrade to 5.10.52
      main/linux-rpi: upgrade to 5.10.55
      community/jool-modules-rpi: rebuild against kernel 5.10.55-r0
      main/zfs-rpi: rebuild against kernel 5.10.55-r0
      main/mosquitto: add secfixes info for CVE-2021-34432
      community/miniupnpd: upgrade to 2.2.2 and refactor
      main/linux-lts: upgrade to 5.10.56
      community/jool-modules-lts: rebuild against kernel 5.10.56-r0
      community/rtl8821ce-lts: rebuild against kernel 5.10.56-r0
      community/rtpengine-lts: rebuild against kernel 5.10.56-r0
      main/dahdi-linux-lts: rebuild against kernel 5.10.56-r0
      main/xtables-addons-lts: rebuild against kernel 5.10.56-r0
      main/zfs-lts: rebuild against kernel 5.10.56-r0
      main/linux-rpi: upgrade to 5.10.56
      community/jool-modules-rpi: rebuild against kernel 5.10.56-r0
      main/zfs-rpi: rebuild against kernel 5.10.56-r0
      main/raspberrypi-bootloader: upgrade to 1.20210727
      main/libretls: remove transitional hack provides
      main/libretls: fix the generation of SO version
      ===== release 3.14.1 =====

Oliver Smith (2):
      community/postmarketos-ondev: upgrade to 0.7.0
      community/pmbootstrap: upgrade to 1.35.0

Sören Tempel (2):
      main/alpine-baselayout: don't append existing entries to $PATH
      main/alpine-baselayout: unset script variable in profile

Thomas Liske (3):
      community/ifstate: upgrade to 1.5.3
      community/ifstate: upgrade to 1.5.4
      community/py3-wgnlpy: upgrade to 0.1.5

Timo Teräs (2):
      main/apk-tools: security upgrade to 2.12.6
      main/apk-tools: upgrade to 2.12.7

macmpi (2):
      main/linux-rpi: add linux-firmware-cypress dependency
      main/linux-firmware: upgrade to 20210716

omni (1):
      community/tor: security upgrade to 0.4.5.9

pexcn (1):
      main/linux-lts: enable CONFIG_NET_SCH_CAKE for config-virt

prspkt (1):
      main/putty: security upgrade to 0.76 (CVE-2021-36367)



ALPINE LINUX 3.14.0 RELEASED
We are pleased to announce the release of Alpine Linux 3.14.0, the first in the v3.14 stable series.

NEW FEATURES AND NOTEWORTHY NEW PACKAGES
Lua 5.4.3
SIGNIFICANT UPDATES
HAProxy 2.4.0
KDE 21.04.2
nginx 1.20.0 and njs 0.5.3
Node.js 14.17.0
Plasma 5.22.0
PostgreSQL 13.3
Python 3.9.5
R 4.1.0
QEMU 6.0.0
XEN 4.15.0
Zabbix 5.4.1
UPGRADE NOTES
As always, make sure to use apk upgrade --available when switching between major versions.
The faccessat2 syscall has been enabled in musl. This can result in issues on docker hosts with older versions of docker (<20.10.0) and libseccomp (<2.4.4), which blocks this syscall.
ClamAV has been moved to community due to lack of long-term upstream support.
LuaJIT package has switched from unmaintained MoonJIT fork to OpenResty’s maintained branch (more info)
NGINX package changed the default directory for the vhost configs from /etc/nginx/conf.d to /etc/nginx/http.d (more info).
collectd package has been split into into subpackages for plugins (more info).
npm package has been moved into a standalone aport (more info).
In nftables, the rate limit for echo-request has been removed from the default ruleset.
fail2ban has been disabled for the time being due to many tests failing. As an alternative, sshguard might be used.
CREDITS
Thanks to everyone sending in patches, bug reports, new and updated aports, and to everyone helping with writing documentation, maintaining the infrastructure, or has contributed in any other way!

Thanks to GIGABYTE, Linode, Fastly, IBM, Equinix Metal, vpsFree and RapidSwitch for providing us with hardware and hosting.

CHANGES
The full list of changes can be found in the wiki, git log and bug tracker.

COMMIT STATISTICS
    12  6543
     1  ALTracer
    31  Adam Jensen
     1  Adam Pimentel
     1  Adeel
     6  Aiden Grossman
     3  Aleks Bunin
     6  Alex Denes
     3  Alex Raschi
    21  Alex Yam
     2  Alexander Brzoska
     2  Alexey Minnekhanov
    13  André Klitzing
    35  Andy Hawkins
   236  Andy Postnikov
    24  Anjandev Momi
     1  Antoine Fontaine
     1  Anton Derevyagin
    69  Antoni Aloy Torrens
   258  Ariadne Conill
  1113  Bart Ribbers
     1  Bhushan Shah
     4  Bobby The Builder
     1  Bor Grošelj Simić
     1  Boris Faure
     1  Bradford D. Boyle
    63  Carlo Landmeter
     1  Carson Page
     2  Chris Kruger
     3  Chris Novakovic
     2  Christine Dodrill
    72  Clayton Craft
     1  Cormac Stephenson
     1  Craig Comstock
    14  Curt Tilmes
     3  DDoSolitary
    80  Damian Kurek
     6  Danct12
     1  Daniel Kolesa
     7  Daniel Néri
     5  Daniel Santana
     1  Dave Henderson
   153  David Demelier
     2  David Florness
     1  David Sugar
     2  Dekedro
    10  Dennis Krupenik
    35  Dermot Bradley
     1  Derriick
     6  Diaz Urbaneja Victor Diego Alenjandro
     1  Diego Jara
     1  Dmitriy Kovalkov
     1  Dominic
     4  Dominik Schulz
     7  Dominique Martinet
    19  Donoban
    56  Drew DeVault
    99  Duncan Bellamy
     1  Durmot Snell
    22  Dylan Van Assche
     2  Emanuele Sorce
     1  Erik Ogan
     1  Fabian Affolter
     2  Francesco Camuffo
   503  Francesco Colista
     1  Frank J. Cameron
     2  Fraser Waters
    72  Galen Abell
    10  Geod24
     1  George Hopkins
     2  GreyXor
     1  GreyXor GreyXor
     2  Haelwenn (lanodan) Monnier
     2  Hani Shawa
    20  Henrik Riomar
    37  Holger Jaekel
     1  Iskren Chernev
     1  Ivan Sokolov
   184  J0WI
    13  Jake Buchholz
   314  Jakub Jirutka
     1  James Stone
     1  Jellyfrog
     1  Jinming Wu, Patrick
     2  Jiri Kastner
     2  Johannes Heimansberg
     4  Johannes Marbach
     1  John Longe
     2  Jonas
     1  Jonathan Albrieux
     4  Jordan Christiansen
     1  Julian P Samaroo
     7  Julian Weigt
    13  JuniorJPDJ
   146  Justin Berthault
     9  Kaarle Ritvanen
     8  Kasper K
     2  Keith Maxwell
   301  Kevin Daudt
    14  Kevin Thomas
     6  KikooDX
     1  Kiyoshi Aman
    45  Konstantin Kulikov
     2  Krystian Chachuła
     1  Lars Kuhtz
    29  Laurent Bercot
  1579  Leo
    20  Leon Marz
    41  Leonardo Arena
    73  Luca Weiss
     7  Lucas Ramage
     5  Maarten van Gompel
    45  Marian Buschsieweke
     7  Martijn Braam
     2  Martin Häger
     8  Martin Kaesberger
     1  Martin Koppehel
     1  Mathew Meins
     6  Matthew T Hoare
     1  Michael Dombrowski
     4  Michael Ekstrand
     1  Michael Giraldo
    12  Michael Pirogov
     2  Michael Truog
     3  Michał Adamski
   640  Michał Polański
     1  Michiel Alexander Boekhoff
     3  Mikael Jenkler
     9  Mike Crute
     1  Mike Gilbert
   272  Milan P. Stanić
     6  Minecrell
     1  Mogens Jensen
  2038  Natanael Copa
     3  Nathan Angelacos
    38  Newbyte
     1  Nick Black
     2  Nico Schottelius
     1  Niek van der Maas
     7  Noel Kuntze
    40  Oleg Titov
    23  Oliver Smith
     3  Olliver Schinagl
     2  Paper
     2  Patrick Gansterer
     1  Patrycja Rosa
     6  Paul Bredbury
     1  Pedro Lucas Porcellis
     1  Peter M
     5  Peter van Dijk
     3  Petr Vorel
     2  R4SAS
     1  Raatty
     1  Ralf Rachinger
     4  Rasmus
   401  Rasmus Thomsen
     2  Reed Wade
     1  Richard Patel
     2  River Dillon
     2  Robert Günzler
     1  Rodrigo Lourenço
     4  Roman Shaposhnik
     7  Rosen Penev
     4  Ryan Barnett
     1  Sabin Iacob
    10  Sean McAvoy
     1  Sebastiaan van Stijn
     1  ShaRose
     1  Shawn Rose
     5  Sheila Aman
     1  Shuanglei Tao
    18  Simon Frankenberger
    11  Simon Rupf
     1  Simon Ser
     8  Siva Mahadevan
     6  Sodface
     1  Stacy Harper
     1  Stefan Hansson
     5  Stefan Krah
     2  Stefan Reiff
   139  Sören Tempel
    67  TBK
     1  Ted Trask
     1  Terra
    39  Thomas Kienlen
    13  Thomas Liske
     2  Tim Weippert
     6  Timo Teräs
    94  Timothy Legge
     9  Tom Lebreux
     1  Tom Payne
     1  TuxThePenguin0
     1  Veovis
     1  Vlatko Kosturjak
     1  Walo
     1  Wesley van Tilburg
    10  Will Sinatra
     1  Wolf
     1  Youfu Zhang
     1  Your Full Name
     4  asdf
     1  david
     1  dkrefft
     4  guddaff
     1  jona
    10  jvoisin
     2  kasperk81
     6  kpcyrd
     1  la Fleur
     1  lafleur
     4  macmpi
     1  matt335672
     1  messense
     1  minus
    18  nibon7
     5  nick
    20  nick black
     1  okzk
   181  omni
     1  opal hart
    16  pglaum
   173  prspkt
    22  rahmanshaber
     5  shhhum
     1  solidnerd
     1  techknowlogick
     2  tronfortytwo
     2  ur4t
     1  vinnie costante
    12  wener
     2  Éloi Rivard
     1  Óliver García Albertos


ALPINE LINUX 3.13.5 RELEASED
The Alpine Linux project is pleased to announce the immediate availability of version 3.13.5 of its Alpine Linux operating system.

This release includes a fix for apk-tools CVE-2021-30139.

The full lists of changes can be found in the git log.

GIT SHORTLOG
6543 (1):
      community/gitea: upgrade to 1.13.7

Andy Postnikov (4):
      community/php7-pecl-mongodb: upgrade to 1.9.1 and modernize
      community/php8-pecl-mongodb: upgrade to 1.9.1 and modernize
      community/php7-pecl-xdebug: upgrade to 3.0.4
      community/php8-pecl-xdebug: upgrade to 3.0.4

Ariadne Conill (4):
      main/apk-tools: add hotfix for tarball parsing DoS (CVE pending)
      main/apk-tools: backout the hotfix, causes sporadic failures
      community/nss: disable binary stripping
      community/xorg-server: fix CVE-2021-3472

Bart Ribbers (3):
      community/maliit-framework: upgrade to 2.0.0
      community/maliit-keyboard: upgrade to 2.0.0
      community/maliit-keyboard: add missing runtime dep on dconf

Duncan Bellamy (1):
      community/ceph: upgrade to 15.2.10 * install dashboard mgr node_modules on install as too large

Francesco Colista (1):
      community/jenkins: security upgrade to 2.287

J0WI (4):
      community/webkit2gtk: security upgrade to 2.32.0
      community/firefox-esr: security upgrade to 78.9.0
      community/nss: upgrade to 3.61
      community/nss: upgrade to 3.62

Jakub Jirutka (2):
      main/ruby: remove man files provided by ruby-bundler
      main/nodejs: fix CVE-2021-27290 in npm subpackage

Justin Berthault (1):
      main/clamav: upgrade to 0.103.2

Kaarle Ritvanen (1):
      community/py3-django-oscar: crash fix

Kevin Daudt (1):
      main/lxc-templates-legacy: account of existing nodes in alpine template

Leo (6):
      community/xterm: fix CVE-2021-27135
      community/xterm: drop fix for CVE-2021-27135
      community/xterm: security upgrade to 367
      main/tar: security upgrade to 1.34
      community/nss: upgrade to 3.63
      community/py3-django: security upgrade to 3.1.8

Leonardo Arena (4):
      main/spamassassin: security upgrade to 3.4.5
      main/spamassassin: update source
      community/nextcloud: upgrade to 20.0.9
      community/nextcloud19: upgrade to 19.0.10

Michał Polański (7):
      community/youtube-dl: upgrade to 2021.04.01
      community/hcloud: upgrade to 1.22.0
      community/ginkgo: upgrade to 1.16.0
      community/hcloud: upgrade to 1.22.1
      community/syncthing: fix CVE-2021-21404
      main/nodejs: security upgrade to 14.16.1
      main/clamav: remove CVE-2021-1386 from secfixes

Milan P. Stanić (4):
      main/lxc: fix cgroup mounting
      main/postfix: upgrade to 3.5.10
      main/irssi: upgrade to 1.2.3
      community/xorg-server: upgrade to 1.20.11

Natanael Copa (15):
      main/asterisk: remove /tmp
      main/linux-rpi: upgrade to 5.10.29
      community/jool-modules-rpi: rebuild against kernel 5.10.29-r0
      main/zfs-rpi: rebuild against kernel 5.10.29-r0
      main/linux-lts: upgrade to 5.10.29
      community/jool-modules-lts: rebuild against kernel 5.10.29-r0
      community/rtl8821ce-lts: rebuild against kernel 5.10.29-r0
      community/rtpengine-lts: rebuild against kernel 5.10.29-r0
      main/dahdi-linux-lts: rebuild against kernel 5.10.29-r0
      main/xtables-addons-lts: rebuild against kernel 5.10.29-r0
      main/zfs-lts: rebuild against kernel 5.10.29-r0
      main/curl: upgrade to 7.76.1 (CVE-2021-22876, CVE-2021-22890)
      main/apk-tools: add secfixes info
      main/busybox: backport tab completion fix
      ===== release 3.13.5 =====

Rasmus Thomsen (8):
      community/cbindgen: upgrade to 0.18.0
      main/cython: depend on python3
      community/firefox: upgrade to 87.0
      community/firefox: build with clang, doesn't OOM on 32-bit
      main/vala: upgrade to 0.50.6
      main/cairo: add patch for CVE-2020-35492
      community/librsvg: security upgrade to 2.50.4
      main/vala: upgrade to 0.50.7

Timo Teräs (1):
      main/apk-tools: upgrade to 2.12.5

matt335672 (1):
      community/libvirt: use correct OpenRC service definitions for libvirt-guests


ALPINE 3.10.9, 3.11.11 AND 3.12.7 RELEASED
The Alpine Linux project is pleased to announce the immediate availability of version 3.10.9, 3.11.11 and 3.12.7 of its Alpine Linux operating system.

Those releases include fixes for apk-tools CVE-2021-30139.

ALPINE LINUX 3.12.0 RELEASED
We are pleased to announce the release of Alpine Linux 3.12.0, the first in the v3.12 stable series.

NEW FEATURES AND NOTEWORTHY NEW PACKAGES
Initial support for mips64 (big endian).
Initial support for D programming language.
SIGNIFICANT UPDATES
Linux 5.4.43
GCC 9.3.0
LLVM 10.0.0
Git 2.24.3
Node.js 12.16.3
Nextcloud 18.0.3
PostgreSQL 12.3
QEMU 5.0.0
Zabbix 5.0.0
UPGRADE NOTES
After upgrading to OpenSSH >= 8.2_p1, the server will not accept new connections until it is restarted
There is no longer a python package providing python2. You need to explicitly install python2 or python3. Additionally, as part of the ongoing work to remove python2, many python2 modules have been removed.
CREDITS
Thanks to everyone sending in patches, bug reports, new and updated aports, and to everyone helping with writing documentation, maintaining the infrastructure, or has contributed in any other way!

Thanks to GIGABYTE, Linode, Fastly, IBM, Packet, vpsFree and RapidSwitch for providing us with hardware and hosting.

CHANGES
The full list of changes can be found in the wiki, git log and bug tracker.

COMMIT STATISTICS
     7  6543
    14  Adam Jensen
     4  Adam Saponara
     1  Alex
     2  Alexander Willing
     1  Andrea Scarpino
     1  Andrew Gunnerson
    15  André Klitzing
     2  Andy Li
   162  Andy Postnikov
    15  Anjandev Momi
    21  Antoine Fontaine
     2  Arda Aytekin
   757  Ariadne Conill
     6  Axel Ulrich
   788  Bart Ribbers
     1  Bob Green
     1  Boris Faure
     2  Bridouz
    16  Carlo Landmeter
     2  Chad Dougherty
     6  Chloe Kudryavtsev
     5  Clayton Craft
     1  Conor Anderson
     1  Cory Sanin
     5  Curt Tilmes
    15  Danct12
     1  Daniel Corbe
     3  Daniel Néri
     7  Daniel Santana
     1  Daniele Debernardi
     1  Dave
     1  Dave Henderson
   111  David Demelier
     1  David Florness
     2  David Heidelberg
     1  Dennis Günnewig
     1  Dermot Bradley
     2  Dmitry Romanenko
     1  Dominic Fung
    38  Drew DeVault
    15  Duncan Bellamy
     1  Eleksir
     1  Eric Molitor
     1  Eric Poelke
     1  Eric Trombly
     1  Erik Larsson
     1  Erik Ogan
     3  Fabian Affolter
   228  Francesco Colista
     2  Frédéric Guillot
    62  Galen Abell
     9  Gennady Feldman
    17  Geod24
     2  Gompa
    10  Guilherme Felipe da Silva
     4  Gustavo L F Walbon
     2  Gustavo Walbon
     3  Haelwenn (lanodan) Monnier
    18  Henrik Riomar
    44  Holger Jaekel
     2  Hristiyan Ivanov
     1  Hugo Rodrigues
     6  Ian Bashford
     4  Ian Douglas Scott
     3  Ibex
     2  Iskren Chernev
     2  Ivan Tham
   287  J0WI
     9  Jake Buchholz
   305  Jakub Jirutka
     2  Jason A. Donenfeld
    11  Jean-Louis Fuchs
     3  Jinming Wu, Patrick
     1  Joel
     1  Johannes Edmeier
     1  John Salmon
     1  Julian Weigt
   135  Justin Berthault
    39  Kaarle Ritvanen
   105  Keith Maxwell
     1  Kenneth Soerensen
   210  Kevin Daudt
     1  Kit
     2  Kohei Nishimura
    40  Konstantin Kulikov
     1  Larry Reaves
  3551  Leo
     2  Leon Marz
    41  Leonardo Arena
     1  Liam Nattrass
    23  Luca Weiss
     6  Lucas Ramage
     1  Ludovic Chabant
    26  Marian Buschsieweke
     1  Mark Pashmfouroush
     3  Mark Zealey
     1  Martijn Braam
     2  Matthias Neugebauer
     4  Michael Aldridge
     1  Michael Forney
     2  Michael John
    17  Michael Pirogov
     1  Michael Truog
     1  Michał Fita
   175  Michał Polański
     8  Mike Crute
     6  Mike Sullivan
     2  Mikhail Snetkov
   185  Milan P. Stanić
    27  Minecrell
     3  Mohammad Abdolirad
     6  Mustang
     1  Natamo
   623  Natanael Copa
     1  Nathan Angelacos
     6  Nero
     1  Niklas Cathor
    63  Oleg Titov
     9  Oliver Smith
     5  Olliver Schinagl
     1  Pablo Castorino
     1  Panagiotis Simakis
     4  Paper
     1  Patrick Gaskin
     1  Patrick Wu
     1  Pedro Filipe
     6  Philipp Glaum
     2  R4SAS
     1  Raatty
   999  Rasmus Thomsen
     3  Reid Rankin
     1  Richard Kojedzinszky
     2  Robert Contreras
     1  Robert Pritzkow
     5  Russ Webber
     1  Sandro Jäckel
     3  Sascha Brawer
     1  Sascha Paunovic
    16  Simon Frankenberger
     5  Simon Rupf
     4  Simon Zeni
    11  Stefan Reiff
     1  Stefano Sasso
     1  Sven Wick
   223  Sören Tempel
   308  TBK
     8  Taner Tas
     3  Ted Trask
     1  Tetsuo NOMRUA
     5  Thomas Kienlen
    19  Thomas Liske
     1  Tim Brust
    13  Timo Teräs
     1  Timotej Lazar
   176  Timothy Legge
     1  Tobias Spieth
     1  Tom Parker-Shemilt
     1  Tom Payne
     1  Tuan Hoang
     3  Ty Sarna
    13  Victor Diego Alegandro Diaz Urbaneja
     4  Victor Diego Alejandro Diaz Urbaneja
     1  VÖRÖSKŐI András
     1  Weilu Jia
     1  Wictor Lund
     4  Will Sinatra
    14  Will sinatra
     1  William Johansson
     2  Winston Weinert
     1  Yaakov Selkowitz
     1  Yonggang Luo
     3  aeeq
     1  allgdante
     1  alpine-mips-patches
    14  alpterry
     1  aptalca
     2  dunk@denkimushi.com
     3  iggy
     4  jirutjak
     1  kjg-ungleich
     2  kohnish@gmx.com
     8  kpcyrd
     4  macmpi
     1  mpmkp2020
     1  msrd0
     2  nathan hensel
     2  nihr43
     9  nixfloyd
     1  ny-a
     6  odidev
     2  pegah.bahramiani
     2  pglaum
     2  prez
    44  prspkt
    43  rahmanshaber
     1  umarcor
     2  viest
    16  wener
     3  xrs
     1  Đoàn Trần Công Danh


ALPINE LINUX 3.11.6 RELEASED
The Alpine Linux project is pleased to announce the immediate availability of version 3.11.6 of its Alpine Linux operating system.

This includes an important security fix for openssl (CVE-2020-1967).

The full lists of changes can be found in the git log.

GIT SHORTLOG
Andy Postnikov (2):
      community/php7: security upgrade to 7.3.17 CVE-2020-7067
      community/cacti: upgrade to 1.2.11

Arda Aytekin (1):
      community/openblas: revert LAPACK changes

Ariadne Conill (2):
      community/tor: disable package pending security review
      community/tor: re-enable and rebuild to avoid bogus IDS warning

Carlo Landmeter (1):
      main/py3-crypto: fix operator

J0WI (6):
      main/apache2: security upgrade to 2.4.43
      main/apache2: modernize
      main/haproxy: security upgrade to 2.0.14
      main/gd: patch CVE-2018-14553 and CVE-2019-11038
      main/libssh: security upgrade to 0.9.4
      main/git: security upgrade to 2.24.2

Jake Buchholz (1):
      community/runc: security upgrade to 1.0.0_rc10

Kaarle Ritvanen (3):
      main/strongswan: subpackage for logfile config
      main/in-sync: backport from edge
      main/dmvpn: file list for in-sync

Keith Maxwell (1):
      [3.11] main/ansible: security upgrade to 2.9.7

Kevin Daudt (1):
      main/git: security upgrade to 2.24.3 (CVE-2020-11008)

Leo (22):
      community/py3-twisted: security upgrade to 20.3.0
      main/bluez: fix CVE-2020-0556
      main/icu: fix CVE-2020-10531
      community/py3-bleach: security upgrade to 3.1.4
      main/libmspack: security upgrade to 0.10.1_alpha
      main/libvpx: add missing secfixes info
      community/nethack: upgrade to 3.6.6
      main/unzip: fix CVE-2019-13232
      community/jenkins: security upgrade to 2.228
      main/unzip: actually fix CVE-2019-13232
      main/screen: fix CVE-2020-9366
      community/dia: fix secfixes comment
      main/gnutls: fix GNUTLS-SA-2020-03-31
      main/libgit2: upgrade to 0.28.5
      main/gnutls: add CVE secfixes info
      main/mbedtls: security upgrade to 2.16.5
      main/bubblewrap: security upgrade to 0.4.1
      main/xen: add missing CVE info
      main/mercurial: upgrade to 5.3.2
      community/freerdp: security upgrade to 2.0.0
      community/wireshark: security upgrade to 3.0.10
      main/xen: fix various security issues

Leonardo Arena (2):
      community/nextcloud: upgrade to 17.0.5
      community/racktables: needs mbstring PHP module

Milan P. Stanić (5):
      community/firefox-esr: upgrade to 68.6.1
      community/firefox-esr: upgrade to 68.7.0
      main/ncurses: fix missing vtXXX terminfo in ncurses-terminfo-base
      main/st: set depends on ncurses-terminfo-base
      testing/st-xrdb: set depends on ncurses-terminfo-base

Natanael Copa (16):
      main/screen: fix patch for CVE-2020-9366
      main/uwsgi: use libucontext for ugreen plugin
      community/graphicsmagick: security upgrade to 1.3.35 (CVE-2020-10938)
      main/freeradius: fix going though post-proxy on dead home server
      main/openssl: security upgrade to 1.1.1g (CVE-2020-1967)
      main/linux-lts: upgrade to 5.4.34 and misc config fixes
      community/jool-modules-lts: rebuild against kernel 5.4.34-r0
      community/virtualbox-guest-modules-lts: rebuild against kernel 5.4.34-r0
      community/wireguard-lts: update to 1.0.20200401 / 5.4.34-r0
      main/drbd-lts: rebuild against kernel 5.4.34-r0
      main/xtables-addons-lts: rebuild against kernel 5.4.34-r0
      main/zfs-lts: rebuild against kernel 5.4.34-r0
      main/linux-rpi: upgrade to 5.4.34
      community/jool-modules-rpi: rebuild against kernel 5.4.34-r0
      community/wireguard-rpi: upgrade to 1.0.20200401 / 5.4.34-r0
      ===== release 3.11.6 =====

Rasmus Thomsen (13):
      main/vala: upgrade to 0.46.7
      community/libwpe: new aport
      community/libwpebackend-fdo: new aport
      community/webkit2gtk: security upgrade to 2.28.0
      community/gjs: upgrade to 1.58.6
      community/mutter: upgrade to 3.34.5
      community/gnome-shell: upgrade to 3.34.5
      community/gnome-control-center: upgrade to 3.34.5
      community/gnome-desktop: upgrade to 3.34.5
      community/gnome-weather: upgrade to 3.34.1
      community/gnome-weather: upgrade to 3.34.2
      community/webkit2gtk: security upgrade to 2.28.1
      main/vala: upgrade to 0.46.8

Robert Pritzkow (1):
      main/ruby: security upgrade to 2.6.6

Sören Tempel (1):
      main/mcpp: fix CVE-2019-14274

Thomas Liske (1):
      main/py-dbus: fix packaging

Timo Teräs (1):
      main/apk-tools: upgrade to 2.10.5

Đoàn Trần Công Danh (1):
      main/git: fix and enable tests


ALPINE LINUX 3.11.5 RELEASED
The Alpine Linux project is pleased to announce the immediate availability of version 3.11.5 of its Alpine Linux operating system.

The full lists of changes can be found in the git log.

The 3.11.4 release was skipped due to an error in release process.

GIT SHORTLOG
dam Jensen (2):
      community/bcc: add static subpackage
      community/libbpf: upgrade to 0.0.6

André Klitzing (1):
      main/mercurial: upgrade to 5.3.1

Andy Postnikov (7):
      community/php7-pecl-xdebug: upgrade to 2.9.1
      community/phpmyadmin: add secfixes
      main/ansible: security upgrade to 2.9.3 CVE-2019-14904 CVE-2019-14905
      main/postfix: upgrade to 3.4.9
      community/php7: security upgrade to 7.3.15
      community/php7: security upgrade to 7.3.16
      community/phpmyadmin: security upgrade to 4.9.5

Bart Ribbers (1):
      community/okular: security upgrade to 19.08.3-r1

Carlo Landmeter (2):
      community/chromium: change maintainer
      main/mariadb: upgrade to 10.4.12 and fix deps

Chad Dougherty (1):
      main/doas: fix simple typo in description

Francesco Colista (3):
      community/live-media: fixed symbol-not-found issue
      community/vlc: bump pkgrel due to upgrade of live-media
      community/mplayer: bump pkgrel due to upgrade of live-media

Holger Jaekel (1):
      community/gdal: upgrade to 3.0.3

J0WI (5):
      main/luajit: add support for s390x
      community/php7: security upgrade to 7.3.14 (CVE-2020-7059 CVE-2020-7060)
      community/openjdk8: security upgrade to 8.242.08
      main/postgresql: security upgrade to 12.2
      community/tor: security upgrade to 0.4.1.9

Jake Buchholz (1):
      main/mariadb: upgrade to 10.4.11

Jakub Jirutka (24):
      community/cesnet-tcs-cli: upgrade to 0.3.0
      community/kea: fix depends_dev
      community/kea: move binary kea-lfc to kea-common, remove subpkg kea-utils
      main/freeradius: fix segfault in process request_running()
      main/opensmtpd: security upgrade to 6.6.2p1
      main/opensmtpd: add secfixes
      community/kea: fix problem with kea service doesn't want to stop
      main/uwsgi: mitigate backward compat. breakage in -python3 and -gevent3
      main/uwsgi: actually add post-upgrade script
      main/sudo: fix CVE-2019-18634
      main/nodejs: upgrade to 12.15.0
      main/nodejs: fix man pages to have npm- prefix
      main/openvpn: allow to pass additional arguments for openvpn
      community/uacme: create acme-challenge dir
      main/libxml2: fix CVE-2020-7595
      main/freeradius: remove sites-available/*.orig
      main/freeradius: fix perms in certs directory
      main/protobuf: fix ruby gem - missing symbol __va_copy
      community/lua-mmdb: new aport (needed for knot-resolver)
      community/knot-resolver: add missing dependencies
      community/knot-resolver: add init script for kres-cache-gc
      main/opensmtpd: security upgrade to 6.6.4p1
      community/cesnet-tcs-cli: upgrade to 0.3.1
      community/cesnet-tcs-cli: upgrade to 0.3.2

Kaarle Ritvanen (5):
      main/awall: upgrade to 1.7.0
      main/py3-django: security upgrade to 1.11.28
      main/awall: upgrade to 1.7.1
      main/dmvpn: fix race condition
      main/dmvpn: various fixes

Kevin Daudt (5):
      ci: silence fetching from upstream
      ci: enable shallow cloning/fetching
      ci: use clone instead of fetch
      community/weechat: security upgrade to 2.7.1 (CVE-2020-8955)
      main/squid: upgrade to 4.10

Leo (34):
      community/google-authenticator: upgrade to 1.08
      main/sudo: don't warn about missing /etc/environment with no PAM
      main/open-iscsi: fix path of commands on initd, add -dev and -libs subpkg
      main/doas: upgrade to 6.6.1
      community/uacme: upgrade to 1.0.22
      community/py3-prettytable: fix permissions
      main/glib: add missing CVE info
      main/glib: upgrade to 2.62.5
      main/ncurses: fix automatic dependency due to symlinks
      main/ncurses: upgrade to 6.1_p20200118
      community/xterm: depend on ncurses-terminfo
      community/alacritty: depend on ncurses-terminfo
      community/gnome-terminal: depend on ncurses-terminfo
      testing/kitty: depend on ncurses-terminfo
      community/konsole: depend on ncurses-terminfo
      main/putty: depend on ncurses-terminfo
      main/ncurses: re-arrange terminfo contents
      {main,community,testing}: make terminals depend on ncurses-terminfo-base
      main/ncurses: move screen-256color to ncurses-terminfo-base
      main/python3: upgrade to 3.8.2
      main/py3-django: upgrade to 1.11.29
      main/libarchive: upgrade to 3.4.2
      community/py3-waitress: upgrade to 1.4.1
      community/py3-bleach: upgrade to 3.1.1
      community/sleuthkit: fix CVE-2020-10232 and CVE-2020-10233
      community/cacti: upgrade to 1.2.10
      main/exiv2: fix CVE-2019-20421
      main/virglrenderer: security upgrade to 0.8.1
      main/gst-plugins-base: add secfixes
      community/py3-bleach: security upgrade to 3.1.2
      main/ansible: security upgrade to 2.9.6
      community/ipmitool: fix CVE-2020-5208
      main/clamav: add missing secfixes info
      main/py3-yaml: security upgrade to 5.3.1

Leonardo Arena (2):
      main/samba: security upgrade to 4.11.5
      community/wireshark: security upgrade to 3.0.8 (CVE-2020-7045)

Milan P. Stanić (15):
      main/iproute2: fix LIBDIR for tc plugins
      community/firefox-esr: upgrade to 68.4.2
      community/gcc6: fix wrong code when returning padded struct
      community/firefox-esr: upgrade to 68.5.0
      main/haproxy: upgrade to 2.0.13
      main/dovecot: security upgrade to 2.3.9.3
      main/ppp: security fix
      community/tvheadend: change pkggroup to video
      community/acme.sh: upgrade to 2.8.5
      main/musl: thumb2 support for arm memcpy
      main/nsd: enable ratelimit configure option
      main/ppp: secfix for radius and EAP
      community/firefox-esr: security upgrade to 68.6.0
      main/gcc: fix wrong code when returning padded struct
      main/musl: backport fixes from 1.2.0

Natanael Copa (39):
      community/chromium: upgrade to 79.0.3945.130
      main/alpine-conf: backport lbu fix for listing ciphers
      main/alpine-conf: unbreak lbu
      main/libebml: fix secfixes comment
      main/lz4: fix secfixes comment
      main/e2fsprogs: fix secfixes comment
      main/faac: fix secfixes comment
      community/sox: fix secfixes comment
      main/zzliplib: fix secfixes comment
      community/containerd: fix whitespace damage in comment
      main/sudo: upgrade to 1.8.31
      community/webkit2gtk: update secfixes comment
      main/openjpeg: secfixes (CVE-2020-6851,CVE-2020-8112)
      main/ca-certificates: fix bundle with certs without newline
      main/libwebsockets: upgrade to 3.2.2
      community/wireshark: security upgrade to 3.0.9
      main/linux-lts: upgrade to 5.4.26
      community/jool-modules-lts: rebuild against kernel 5.4.26-r0
      community/virtualbox-guest-modules-lts: rebuild against kernel 5.4.26-r0
      community/wireguard-lts: rebuild against kernel 5.4.26-r0
      main/drbd-lts: rebuild against kernel 5.4.26-r0
      main/xtables-addons-lts: rebuild against kernel 5.4.26-r0
      main/zfs-lts: rebuild against kernel 5.4.26-r0
      main/linux-rpi: add check to verify kernel version
      main/linux-rpi: upgrade to 5.4.26
      community/jool-modules-rpi: rebuild against kernel 5.4.26-r0
      community/wireguard-rpi: rebuild against kernel 5.4.26-r0
      main/raspberrypi-bootloader: upgrade to 1.20200212
      main/linux-lts: upgrade to 5.4.27
      community/jool-modules-lts: rebuild against kernel 5.4.27-r0
      community/virtualbox-guest-modules-lts: rebuild against kernel 5.4.27-r0
      community/wireguard-lts: rebuild against kernel 5.4.27-r0
      main/drbd-lts: rebuild against kernel 5.4.27-r0
      main/xtables-addons-lts: rebuild against kernel 5.4.27-r0
      main/zfs-lts: rebuild against kernel 5.4.27-r0
      main/linux-rpi: upgrade to 5.4.27
      community/jool-modules-rpi: rebuild against kernel 5.4.27-r0
      community/wireguard-rpi: rebuild against kernel 5.4.27-r0
      ===== release 3.11.5 =====

Rasmus Thomsen (9):
      community/webkit2gtk: upgrade to 2.26.3
      community/orca: upgrade to 3.34.2
      main/vala: upgrade to 0.46.6
      community/webkit2gtk: upgrade to 2.26.4
      main/zfs: upgrade to 0.8.3
      main/zfs-lts: use zfs 0.8.3
      main/zfs: fix paths in /etc/zfs/zfs{,-functions}
      community/librsvg: add missing secinfo for CVE-2019-20446
      main/glib: upgrade to 2.62.6

Sören Tempel (2):
      main/openrc: fix do_unmount function
      main/musl: update URL and sources

TBK (1):
      main/cvs: security upgrade to 1.12.12

Ted Trask (3):
      main/acf-core: upgrade to 0.22.0
      main/acf-alpine-baselayout: upgrade to 0.13.3
      main/acf-lib: upgrade to 0.11.0

Thomas Liske (1):
      main/iptables: restore lost init.d script for ebtables


ALPINE LINUX 3.11.3 RELEASED
The Alpine Linux project is pleased to announce the immediate availability of version 3.11.3 of its Alpine Linux operating system.

The full lists of changes can be found in the git log.

GIT SHORTLOG
Andy Postnikov (2):
      community/drupal7: security upgrade to 7.69
      community/phpmyadmin: upgrade to 4.9.4

Bart Ribbers (1):
      community/kdeconnect: add missing runtime dep sshfs

Carlo Landmeter (1):
      community/lua-turbo: add missing ca-certificates

Henrik Riomar (1):
      main/etckeeper: upgrade to 1.18.13

J0WI (2):
      main/openvpn: upgrade to 2.4.8
      community/firefox-esr: security upgrade to 68.4.1

Jakub Jirutka (12):
      community/kea: upgrade to 1.7.3
      community/jetty-runner: upgrade to 9.4.15.20190215
      community/repmgr: upgrade to 5.0.0
      community/lua-busted: upgrade to 2.0.0
      community/kea: fix capabilities
      community/kea-hook-runscript: rebuild against kea 1.7.3
      community/kea-hook-runscript: take over maintainership
      community/ruby-rspec-support: upgrade to 3.9.2
      community/muacme: fix depends on cmd:openssl
      community/ldap-passwd-webui: fix depends on py-waitress
      community/py3-waitress: fix broken upgrade from older versions
      main/openrc: allow to change interfaces config location

Jason A. Donenfeld (1):
      community/wireguard: update to 20191226

Joel (1):
      main/linux-lts: enable cannonlake pinctrl for x86_64

Kaarle Ritvanen (2):
      main/awall: upgrade to 1.6.13
      main/ulogd: fix logrotate pattern

Kevin Daudt (1):
      community/salt: fix python3.8 incompattibilities

Leo (6):
      community/dia: fix CVE-2019-19451.patch
      main/python3: upgrade to 3.8.1
      testing/fontforge: rebuild against python3.8
      community/ruby-rspec-mocks: upgrade to 3.9.1
      community/ruby-rspec-core: upgrade to 3.9.1
      main/e2fsprogs: security upgrade to 1.45.5

Leonardo Arena (5):
      main/xen: add secinfo
      main/msmtp: fix init script
      community/lxcfs: let lxc use lxcfs if installed
      community/pflogsumm: remove sysklogd dependency
      main/xen: add secinfo

Milan P. Stanić (6):
      main/haproxy: upgrade to 2.0.12
      main/linux-lts: upgrade to 5.4.7
      main/linux-lts: set UEVENT_HELPER_PATH for armv7
      main/linux-lts: upgrade to 5.4.8
      main/linux-lts: upgrade to 5.4.11
      main/linux-lts: upgrade to 5.4.12

Natanael Copa (34):
      community/chromium: upgrade to 79.0.3945.88
      community/chromium: fix build on armv7
      main/py3-django: security upgrade to 1.11.27 (CVE-2019-19844)
      main/openssl: fix CVE-2019-1551
      community/opensc: security upgrade to 0.20.0
      main/samba: backport fix for python 3.8
      main/hunspell: fix CVE-2019-16707
      community/jool-modules-lts: rebuild against kernel 5.4.8-r0
      community/virtualbox-guest-modules-lts: rebuild against kernel 5.4.8-r0
      community/wireguard-lts: rebuild against kernel 5.4.8-r0
      main/drbd-lts: rebuild against kernel 5.4.8-r0
      main/xtables-addons-lts: rebuild against kernel 5.4.8-r0
      main/zfs-lts: rebuild against kernel 5.4.8-r0
      main/linux-rpi: upgrade to 5.4.7
      main/linux-rpi: upgrade to 5.4.8
      community/jool-modules-rpi: rebuild against kernel 5.4.8-r0
      community/wireguard-rpi: rebuild against kernel 5.4.8-r0
      main/libjpeg-turbo: security upgrade to 2.0.4 (CVE-2019-2201)
      main/kamailio: increase timout for stopping service
      main/busybox: enable FEATURE_NSLOOKUP_BIG
      main/linux-rpi: upgrade to 5.4.12
      community/wireguard-rpi: rebuild against kernel 5.4.12-r0
      community/jool-modules-rpi: rebuild against kernel 5.4.12-r0
      main/linux-lts: enable rtw88 driver for x86/x86_64
      main/linux-lts: enable serial_ir module
      community/jool-modules-lts: rebuild against kernel 5.4.12-r1
      community/virtualbox-guest-modules-lts: rebuild against kernel 5.4.12-r1
      community/wireguard-lts: rebuild against kernel 5.4.12-r1
      main/drbd-lts: rebuild against kernel 5.4.12-r1
      main/xtables-addons-lts: rebuild against kernel 5.4.12-r1
      main/zfs-lts: rebuild against kernel 5.4.12-r1
      main/nginx: fix CVE-2019-20372
      main/mkinitfs: upgrade to 3.4.5
      ==== release 3.11.3 ====

Rasmus Thomsen (18):
      community/py3-keepass: use Cryptodome instead of Crypto
      community/gnome-passwordsafe: use Cryptodome instead of Crypto
      community/accerciser: upgrade to 3.34.3
      community/mutter: upgrade to 3.34.3
      community/gnome-shell: upgrade to 3.34.3
      community/dconf-editor: upgrade to 3.34.3
      community/eog: upgrade to 3.34.2
      community/epiphany: upgrade to 3.34.3.1
      community/gnome-boxes: upgrade to 3.34.3
      community/seahorse: upgrade to 3.34.1
      community/gnome-contacts: upgrade to 3.34.1
      community/rhythmbox: upgrade to 3.4.4
      community/gnome-music: upgrade to 3.34.3
      community/gnome-initial-setup: upgrade to 3.34.3
      community/gnome-maps: upgrade to 3.34.3
      community/evolution-data-server: upgrade to 3.34.3
      community/evolution: upgrade to 3.34.3
      community/evolution-ews: upgrade to 3.34.3

Stefan Reiff (3):
      community/wireguard-rpi: enable for rpi4
      main/libvirt: qemu: Fix migration without parameters
      community/wireguard-(lts|rpi): upgrade to 0.0.20200105

Sören Tempel (1):
      main/ctags: enable tests on s390x again

William Johansson (1):
      main/grub: fix booting Xen under EFI


ALPINE LINUX 3.11.2 RELEASED
The Alpine Linux project is pleased to announce the immediate availability of version 3.11.2 of its Alpine Linux operating system.

This is a bugfix release that fixes missing dtbs files for rpi and missing initramfs image for netboot.

The full lists of changes can be found in the git log and bug tracker.

GIT SHORTLOG
Andy Postnikov (1):
      community/php7: security upgrade to 7.3.13

Jakub Jirutka (4):
      community/clsync: add init script
      community/kea: take over maintainership
      main/pcre2: fix bug causing rspamd segfault
      community/alpine-make-vm-image: upgrade to 0.6.0

Leo (2):
      main/rsyslog: enable Input Module Docker
      community/mongo-c-driver: remove obsolete comment and re-enable on all arches

Leonardo Arena (1):
      main/clamav: add secinfo

Milan P. Stanić (1):
      main/linux-lts: upgrade to 5.4.6

Natanael Copa (20):
      community/jool-modules-lts: rebuild against kernel 5.4.6-r0
      community/virtualbox-guest-modules-lts: rebuild against kernel 5.4.6-r0
      community/wireguard-lts: rebuild against kernel 5.4.6-r0
      main/drbd-lts: rebuild against kernel 5.4.6-r0
      main/xtables-addons-lts: rebuild against kernel 5.4.6-r0
      community/cacti: add secfixes comment
      main/zfs-lts: rebuild against kernel 5.4.6-r0
      main/monit: fix invalid use of vfork
      main/linux-rpi: fix dtbs location
      main/linux-rpi: upgrade to 5.4.6
      community/jool-modules-rpi: rebuild against kernel 5.4.6-r0
      community/wireguard-rpi: rebuild against kernel 5.4.6-r0
      community/hexchat: build with python3-embed
      main/cyrus-sasl: fix CVE-2019-19906
      main/zstd: fix bus error on armhf
      community/go: depen on binuutils-gold on arm*/aarch64
      main/expat: re-enable static library
      scripts/mkimg.netboot.sh: make initramfs readable
      ==== release 3.11.1 ====
      ==== release 3.11.2 ====

Rasmus Thomsen (3):
      community/gedit-plugins: add missing dep on libpeas-python3
      community/shadow: add pam file for newusers
      main/glib: upgrade to 2.62.4

prspkt (2):
      community/hexchat: upgrade to 2.14.3
      community/hexchat: modernize


ALPINE LINUX 3.11.0 RELEASED
We are pleased to announce the release of Alpine Linux 3.11.0, the first in the v3.11 stable series.

NEW FEATURES AND NOTEWORTHY NEW PACKAGES
Linux 5.4 kernel (linux-lts)
Support for Raspberry Pi 4 (aarch64 and armv7)
Initial GNOME and KDE support
Support for Vulkan
MinGW-w64 and DXVK support
Rust is available on all architectures except s390x
SIGNIFICANT UPDATES
Linux 5.4.5
GCC 9.2.0
Busybox 1.31.1
musl libc 1.1.24
LLVM 9.0.0
Go 1.13.4
Node.js 12.14.0
Python 3.8.0
Perl 5.30.1
Postgresql 12.1
Ruby 2.6.5
Rust 1.39.0
Crystal 0.31.1
Erlang 22.1
Zabbix 4.4.3
Nextcloud 17.0.2
Git 2.24.1
Xen 4.13.0
Qemu 4.2.0
UPGRADE NOTES:
linux-vanilla has been removed. Install linux-lts when upgrading.
Python 2 is deprecated. Majority of Python 2 packages was removed and will be completely removed in next release.
Packages now use /var/mail instead of /var/spool/mail, in accordance with FHS
clamav-libunrar is no longer a hard dependency of clamav and needs to be manually installed.
CREDITS
Thanks to everyone sending in patches, bug reports, new and updated aports, and to everyone helping with writing documentation, maintaining the infrastructure, or has contributed in any other way!

Thanks to GIGABYTE, Linode, Fastly, IBM, Packet, vpsFree and RapidSwitch for providing us with hardware and hosting.

CHANGES
The full list of changes can be found in the git log and bug tracker.

COMMIT STATISTICS
     3  6543
     5  Adam Dobrawy
     6  Adam Jensen
     2  Adriaan Groenenboom
     1  Ahmed Bilal Khalid
     1  Alex Mirski-Fitton
     1  Alex Raschi
     6  Alexander Sack
     1  Andrew
     5  André Klitzing
     5  Andy Li
   151  Andy Postnikov
     1  Anirudh Oppiliappan
     6  Antoine Fontaine
    10  Ariadne Conill
   593  Bart Ribbers
     1  Bastien Durel
     1  Bhushan Shah
     2  Boris Faure
     1  Bradley Saulteaux
     1  Bug Fest
     1  Bwko
    43  Carlo Landmeter
     1  Charles Pritchard
    31  Chloe Kudryavtsev
     4  Christian Franke
     1  Christian Schlack
     1  Chunfeng Zhang
     5  Claas Augner
     1  Colin Williams (coliwill)
     2  Cosmo Borsky
     4  Curt Tilmes
     8  Danct12
     2  Daniel Isaksen
     6  Daniele Debernardi
     1  Dave Henderson
     1  Dave Johansen
     1  David Heidelberg
     2  David Sugar
     1  Dmitry Romanenko
    61  Drew DeVault
     2  Eivind Uggedal
     1  Elan Ruusamäe
     1  Eric Poelke
     2  Erik Larsson
     7  Fabian Affolter
     1  Fernando Casas Schössow
   398  Francesco Colista
     1  Frédéric Guillot
    14  Galen Abell
     2  Gavin Howard
    14  Gennady Feldman
     4  Geod24
     2  Guilherme Felipe da Silva
     1  Guillaume Martinez
     5  Henrik Nilsson
    18  Henrik Riomar
    50  Holger Jaekel
     1  Hosh
    14  Ian Bashford
     1  Ian Douglas Scott
     6  Iggy Jackson
     2  Israel Rodrigo Faria
     2  Ivan Delalande
     1  Ivan Tham
   253  J0WI
     1  Jack O'Sullivan
     1  JailBox
    15  Jake Buchholz
   221  Jakub Jirutka
     2  Jan Tatje
     1  Jeremy O'Brien
     1  Jirka Dutka
     3  Joe Holden
    39  Joe Searle
     1  John Gunnarsson
     2  JonathanS
     3  Joonas Kuorilehto
     4  Joseph Benden
     1  Joseph Burt
     1  Joshua Haase
    20  Kaarle Ritvanen
    10  Keith Maxwell
   147  Kevin Daudt
    31  Konstantin Kulikov
     1  Kyle Parisi
     1  Kylie McClain
     1  Laurent Bercot
  4357  Leo
   119  Leonardo Arena
     3  Li Q
     1  Linux User
    23  Luca Weiss
     5  Lucas Ramage
     1  Marco Dickert
    40  Marian Buschsieweke
     2  Mark Weston
     9  Martijn Braam
    12  Matthias Neugebauer
     4  Michael Aldridge
     1  Michael Koloberdin
    17  Michael Pirogov
     1  Michael Truog
     3  Michal Artazov
     1  Mickaël Remars
     2  Mike Crute
    43  Mike Sullivan
     1  Milan P. Stanic
   178  Milan P. Stanić
     2  Minecrell
     1  MrBiTs
     2  Mustang
  2051  Natanael Copa
     3  Nathan Angelacos
     1  Nathan Caldwell
     6  Nathan Owens
     2  Nico Schottelius
     1  Noam Preil
    68  Oleg Titov
     3  Oliver Smith
    19  Olliver Schinagl
     2  Ondrej Exner
     2  Otto Modinos
     1  Pascal Vorwerk
     1  Patrick Wu
     7  Paul Bredbury
     2  Paul Morgan
     6  Pedro Filipe
     4  Philippe Schommers
     1  Phillip Jaenke
     3  R4SAS
   585  Rasmus Thomsen
     9  Robert Sacks
     1  Robert White
     3  Russ
     9  Russ Webber
     1  Rémi Lefèvre
     1  Samuel Hunter
     1  Sandro Jäckel
     1  Sasha Gerrand
     5  Sergey Safarov
     3  Shyam Sunder
     1  Simon F
     6  Simon Frankenberger
    22  Stefan Reiff
    12  Stuart Cardall
     1  Sven Wick
   125  Sören Tempel
    21  TBK
     4  Taner Tas
     3  Ted Trask
     1  Terror
     1  Tetsuo NOMURA
     2  Thomas Kienlen
    11  Tim Brust
    11  Timo Teräs
     6  Timothy Legge
     3  Tom Parker-Shemilt
     1  Tom Payne
    14  Tuan Hoang
     1  Ventz Petkov
     4  Vicente Bergas
     1  Victor Diego Alegandro Diaz Urbaneja
     1  VÖRÖSKŐI András
    11  Will Sinatra
     1  Will sinatra
     2  Wolf
     1  Yonggang Luo
     1  allgdante
    11  alpine-mips-patches
     1  aptalca
     1  b17wise
     1  fgma
     8  iggy
     1  jchipmunk
     6  kpcyrd
     1  macmpi
     2  marmota
     1  ntaylor1781
     2  opal hart
    16  ossdev
     1  ossdev07
     1  pietro
   400  prspkt
    62  rahmanshaber
     1  shrizza
     9  stf
    38  tcely
     1  tony mancill
     2  viest
    10  wener
     1  wenerme
     1  xcko



ALPINE LINUX 3.10.3 RELEASED
The Alpine Linux project is pleased to announce the immediate availability of version 3.10.3 of its Alpine Linux operating system.

The full lists of changes can be found in the git log and gitlab .

GIT SHORTLOG
Alex Mirski-Fitton (1):
      main/openssl: Fix openssl secfix version number

Andy Postnikov (3):
      main/tzdata: upgrade to 2019b
      community/php7: security upgrade to 7.3.9 (CVE-2019-13224)
      community/phpmyadmin: security upgrade to 4.9.1 - CVE-2019-12922

Carlo Landmeter (3):
      community/tvheadend: upgrade to 4.2.8
      main/multipath-tools: fix udev location
      main/multipath-tools: update checksums

Francesco Colista (5):
      main/nghttp2: upgrade to 1.39.1
      main/nghttp2: security upgrade to 1.39.2
      main/sdl2_image: upgrade to 2.0.5
      main/sdl2_image: security upgrade to 2.0.5
      communuty/jenkins: security upgrade to 2.199

Henrik Riomar (1):
      community/intel-ucode: upgrade to 20190918

J0WI (15):
      main/dovecot: security upgrade to 2.3.7.2
      community/firefox-esr: security update to 60.9.0
      community/exim: security upgrade to 4.92.2
      community/libreoffice: security upgrade to 6.2.7.1
      main/openssl: security upgrade to 1.1.1d
      main/ghostscript: add security patches
      main/curl: security upgrade to 7.66.0
      community/openjdk8: security upgrade to 8.222.10
      community/ceph: security upgrade to 14.2.3
      community/exim: patch CVE-2019-16928
      main/libgcrypt: security upgrade to 1.8.5
      main/openssh: security upgrade to 8.1p1
      community/imagemagick6: upgrade to 6.9.10.62
      community/imagemagick6: security upgrade to 6.9.10.68
      main/tzdata: upgrade to 2019c

Jake Buchholz (1):
      [3.10] community/containerd: upgrade to 1.2.9

Jakub Jirutka (4):
      community/cesnet-tcs-cli: upgrade to 0.1.2
      community/cesnet-tcs-cli: upgrade to 0.1.3
      community/uacme: upgrade to 1.0.20
      community/uacme: backport patch fixing uacme.sh

Kaarle Ritvanen (6):
      main/awall: upgrade to 1.6.11
      main/awall: upgrade to 1.6.12
      main/ulogd: include logrotate config
      main/dmvpn: upgrade to 1.2.0
      community/zoneminder: add missing symlink and deps
      main/dmvpn: upgrade to 1.2.1

Kevin Daudt (6):
      gitlab-ci: enable for 3.10-stable
      main/libgcrypt: fix typo in -static description
      gitlab-ci: add build job for aarch64
      gitlab-ci: temporarily disable s390x
      gitlab-ci: revert temporarily disable s390x
      gitlab-ci: update to latest changes

Leo (17):
      main/libx11: provide static libraries in libx11-static
      main/ansible: security upgrade to 2.8.4
      main/wavpack: fix a few CVEs
      main/openldap: security upgrade to 2.4.48
      main/irssi: security upgrade to 1.2.2
      main/varnish: security upgrade to 6.2.1
      main/expat: fix CVE-2019-15903
      main/expat: security upgrade to 2.2.8
      main/mosquitto: fix CVE-2019-11779
      community/httpie: security upgrade to 1.0.3
      community/wireshark: security upgrade to 3.0.4
      community/wireshark: fix source=
      main/sqlite: fix CVE-2019-16168
      main/ruby: security upgrade to 2.5.7
      main/faad2: security upgrade to 2.9.0
      main/e2fsprogs: fix CVE-2019-5094
      main/sshguard: fix handling of shutdown signal

Leonardo Arena (21):
      community/libreoffice: security upgrade to 6.2.6.2
      main/freeradius: security fix (CVE-2019-10143)
      main/kamailio: upgrade to 5.2.4
      main/nodejs: security upgrade to 10.16.3
      main/tiff: security fix (CVE-2019-14973)
      community/zabbix: upgrade to 4.2.6
      community/firefox-esr: update secinfo
      main/ghostscript: security fix (CVE-2019-14817)
      main/asterisk: security fixes
      main/hostapd: security fix (CVE-2019-16275)
      main/wpa_supplicant: security fix (CVE-2019-16275)
      Revert "community/firefox-esr: update secinfo"
      community/milter-greylist: start daemon after network
      main/poppler: security fix (CVE-2019-9959)
      main/poppler: add secinfo
      main/nfdump: security upgrade to 1.6.18
      community/nextcloud: upgrade to 16.0.5
      community/milter-greylist: typo in init script
      main/bacula: upgrade to 9.4.4
      main/bacula: create bacula user for client package
      main/bacula: use root as rundir owner for bacula-client

Milan P. Stanić (15):
      main/haproxy: upgrade to 2.0.5
      main/dovecot: upgrade to 2.3.7.1
      main/postgresql: fix psql segmentation fault
      main/clamav: upgrade to 0.101.4
      main/haproxy: upgrade to 2.0.6
      main/lxc: add init.lxc.static
      main/linux-vanilla: increase number of CPUs
      linux-vanilla: enable xfrm-interface for x86 and x86_64 linux-virt
      main/haproxy: upgrade to 2.0.7
      main/postfix: upgrade to 3.4.7
      main/libpcap: upgrade to 1.9.1
      main/tcpdump: upgrade to 4.9.3
      main/linux-vanilla: enable CONFIG_BLK_DEV_THROTTLING
      community/mumble: upgrade to stable 1.3.0 release
      main/openresolv: upgrade to 3.9.2

Natanael Copa (81):
      community/miniupnpd: rebuild against iptables 1.8
      main/collectd: rebuild against iptables 1.8
      community/vlc: security upgrade to 3.0.8
      main/flite: fix underlinking
      main/lua-bit32: fix upgrade from lua-bitlib
      main/asterisk: rebuild against pjproject 2.8
      main/linux-vanilla: enable dm-writecache
      main/linux-vanilla: upgrade to 4.19.75
      community/virtualbox-guest-modules-vanilla: rebuild against kernel 4.19.75-r0
      community/wireguard-vanilla: rebuild against kernel 4.19.75-r0
      main/dahdi-linux-vanilla: rebuild against kernel 4.19.75-r0
      main/devicemaster-linux-vanilla: rebuild against kernel 4.19.75-r0
      main/drbd-vanilla: rebuild against kernel 4.19.75-r0
      main/xtables-addons-vanilla: rebuild against kernel 4.19.75-r0
      main/zfs-vanilla: rebuild against kernel 4.19.75-r0
      testing/ipt-netflow-vanilla: rebuild against kernel 4.19.75-r0
      main/linux-rpi: upgrade to 4.19.75
      community/wireguard-rpi: rebuild against kernel 4.19.75-r0
      main/linux-rpi: upgrade to 4.19.76
      community/wireguard-rpi: rebuild against kernel 4.19.76-r0
      main/linux-vanilla: upgrade to 4.19.76
      community/virtualbox-guest-modules-vanilla: rebuild against kernel 4.19.76-r0
      community/wireguard-vanilla: rebuild against kernel 4.19.76-r0
      main/dahdi-linux-vanilla: rebuild against kernel 4.19.76-r0
      main/devicemaster-linux-vanilla: rebuild against kernel 4.19.76-r0
      main/drbd-vanilla: rebuild against kernel 4.19.76-r0
      main/xtables-addons-vanilla: rebuild against kernel 4.19.76-r0
      main/zfs-vanilla: rebuild against kernel 4.19.76-r0
      main/linux-vanilla: upgrade to 4.19.78
      community/virtualbox-guest-modules-vanilla: rebuild against kernel 4.19.78-r0
      community/wireguard-vanilla: rebuild against kernel 4.19.78-r0
      main/dahdi-linux-vanilla: rebuild against kernel 4.19.78-r0
      main/devicemaster-linux-vanilla: rebuild against kernel 4.19.78-r0
      main/drbd-vanilla: rebuild against kernel 4.19.78-r0
      main/xtables-addons-vanilla: rebuild against kernel 4.19.78-r0
      main/zfs-vanilla: rebuild against kernel 4.19.78-r0
      testing/ipt-netflow-vanilla: rebuild against kernel 4.19.78-r0
      main/openssh: fix segfault with VerifyHostKeyDNS=yes
      main/openssh: fix build
      main/python3: security upgrade to 3.7.5 (CVE-2019-16056)
      main/libssh2: security upgrade to 1.9.0 (CVE-2019-13115)
      community/go: upgrade to 1.12.10
      main/libssh2: fix for CVE-2019-17498
      main/python3: reduce number of unit tests for PGO
      main/python3: add CVE-2019-16935 to secfixes comment
      main/mariadb: fix build by enable pam
      main/linux-rpi: upgrade to 4.19.79
      main/linux-vanilla: upgrade to 4.19.79
      community/virtualbox-guest-modules-vanilla: rebuild against kernel 4.19.79-r0
      community/wireguard-vanilla: rebuild against kernel 4.19.79-r0
      main/dahdi-linux-vanilla: rebuild against kernel 4.19.79-r0
      main/devicemaster-linux-vanilla: rebuild against kernel 4.19.79-r0
      main/drbd-vanilla: rebuild against kernel 4.19.79-r0
      main/xtables-addons-vanilla: rebuild against kernel 4.19.79-r0
      main/zfs-vanilla: rebuild against kernel 4.19.79-r0
      testing/ipt-netflow-vanilla: rebuild against kernel 4.19.79-r0
      main/openresolv: add compat symlinks
      scripts/genrootfs.sh: fix permissions of / in minirootfs
      community/chromium: upgrade to 76
      community/chromium: upgrade to 76.0.3809.132
      community/chromium: upgrade to 77.0.3865.75
      community/chromium: fix build on armv7
      community/chromium: upgrade to 77.0.3865.90
      community/chromium: upgrade to 77.0.3865.120
      main/python3: disable test threading on arm*
      community/go: upgrade to 1.12.11
      community/go: update secfixes comments
      main/linux-vanilla: upgrade to 4.19.80
      community/virtualbox-guest-modules-vanilla: rebuild against kernel 4.19.80-r0
      community/wireguard-vanilla: rebuild against kernel 4.19.80-r0
      main/dahdi-linux-vanilla: rebuild against kernel 4.19.80-r0
      main/devicemaster-linux-vanilla: rebuild against kernel 4.19.80-r0
      main/drbd-vanilla: rebuild against kernel 4.19.80-r0
      main/xtables-addons-vanilla: rebuild against kernel 4.19.80-r0
      main/zfs-vanilla: rebuild against kernel 4.19.80-r0
      testing/ipt-netflow-vanilla: rebuild against kernel 4.19.80-r0
      community/go: upgrade to 1.12.12
      main/linux-rpi: upgrade to 4.19.80
      community/wireguard-rpi: rebuild against kernel 4.19.80-r0
      main/raspberrypi-bootloader: upgrade to 1.20190925
      ==== release 3.10.3 ====

Ondrej Exner (1):
      main/imap: SNI patch required for TLS 1.3

Rasmus Thomsen (3):
      community/webkit2gtk: add secfixes
      main/zfs: upgrade to 0.8.2
      main/zfs-vanilla: rebuild against ZFS 0.8.2

Stefan Reiff (6):
      main/lmdb: upgrade to 0.9.24
      main/ldb: upgrade to 1.5.5
      main/samba: upgrade to 4.10.8
      main/python3: upgrade to 3.7.4 and enable optimizations
      community/php7: upgrade to 7.3.10
      main/mariadb: upgrade to 10.3.18

Ted Trask (3):
      main/acf-core: upgrade to 0.21.2
      main/acf-jquery: upgrade to 0.4.3
      main/acf-core: upgrade to 0.21.3

Timo Teräs (1):
      scripts/bootstrap.sh: fix openssh bootstrap


ALPINE LINUX 3.10.2 RELEASED
The Alpine Linux project is pleased to announce the immediate availability of version 3.10.2 of its Alpine Linux operating system.

The full lists of changes can be found in the git log and gitlab .

GIT SHORTLOG
Andy Postnikov (1):
      community/php7: security upgrade 7.3.8 - CVE-2019-11041 - CVE-2019-11041

Carlo Landmeter (7):
      testing/docker-compose: upgrade to 1.24.1
      testing/docker-compose: move to community
      community/docker-compose: update checksums
      testing/py3-cached-property: move to community
      testing/py3-dockerpty: move to community
      testing/py3-pysocks: move to community
      testing/py3-texttable: move to community

Henrik Riomar (2):
      main/irqbalance: fix missing socket dir
      main/xen: security upgrade to 4.12.1

J0WI (12):
      main/mozjs60: security upgrade to 60.7.2
      main/mozjs60: upgrade to 60.8.0
      community/firefox-esr: security upgrade to 60.8.0
      community/imagemagick6: security upgrade to 6.9.10-53
      community/imagemagick6: security upgrade to 6.9.10.55
      main/mariadb: security upgrade to 10.3.17
      community/libreoffice: security upgrade to 6.2.5.2
      main/imagemagick: security upgrade to 7.0.8-56
      main/imagemagick: security upgrade to 7.0.8-58
      main/nginx: security upgrade to 1.16.1
      community/ffmpeg: security upgrade to 4.1.4
      main/apache2: upgrade to 2.4.41

Jake Buchholz (1):
      community/docker: upgrade to 18.09.8

Jakub Jirutka (7):
      main/alpine-git-mirror-syncd: security upgrade to 0.3.1
      community/esh: upgrade to 0.3.0
      community/openjdk8: add missing nss dependency to -jre-base
      community/ruby-nokogiri: security upgrade to 1.10.4
      community/imagemagick6: upgrade to 6.9.10.60
      community/ruby-nokogiri: rebuild against libxml 2.9.9
      community/alpine-make-rootfs: upgrade to 0.3.1

Kaarle Ritvanen (1):
      main/dmvpn: upgrade to 1.1.0

Leo (26):
      main/avahi: fix CVE-2017-6519 and CVE-2018-1000845
      main/libxkbcommon: provide static library
      main/keyutils: link libkeyutils.so to ../../lib/libkeyutils.so.1
      community/libraw: add missing CVEs to secfixes comment
      community/openexr: fix CVE-2018-18444
      community/gvfs: security upgrade to 1.40.2
      main/libcroco: fix a few CVEs
      community/libosinfo: fix CVE-2019-13313
      testing/docker-compose: add shell completion subpackages
      main/patch: fix CVE-2019-13636
      main/zeromq: security upgrade to 4.3.2
      community/sox: backport a few CVEs
      main/libtasn1: security upgrade to 4.14
      main/sdl2: security upgrade to 2.0.10
      main/libgcrypt: fix CVE-2019-12904
      community/exim: security upgrade to 4.92.1
      community/vlc: fix CVE-2019-13602
      main/libebml: add secfixes comment for CVE-2019-13615
      main/redis: add secfixes comment
      community/wireshark: security upgrade to 3.0.3
      community/pdns: security upgrade to 4.1.11
      main/subversion: security upgrade to 1.12.2
      main/py-django: security upgrade to 1.11.23
      community/elogind: depend on shadow
      community/ffmpeg: remove duplicate secfixes
      main/cups: security upgrade to 2.2.12

Leonardo Arena (9):
      community/nextcloud: upgrade to 16.0.3
      community/zabbix: upgrade to 4.2.4
      main/kamailio: fix memleak in mohqueue module
      community/zabbix: upgrade to 4.2.5
      main/patch: security fixes
      main/pango: security fix (CVE-2019-1010238)
      main/wpa_supplicant: security fix (CVE-2019-13377)
      main/hostapd: security fixes (CVE-2019-13377)
      community/nextcloud: upgrade to 16.0.4

Matthias Neugebauer (1):
      community/vault: security upgrade to 1.1.1

Milan P. Stanić (4):
      main/haproxy: upgrade to 2.0.3
      main/haproxy: upgrade to 2.0.4
      main/postgresql: security upgrade to 11.5
      main/linux-vanilla: add usb module for sun4i boards fixes #10677

Natanael Copa (34):
      community/webkit2gtk: upgrade to 2.24.3 and enable on arm
      community/webkit2gtk: enable on x86
      main/py-django: security upgrade to 1.11.22 (CVE-2019-12781)
      main/freeswitch: upgrade to 1.8.7
      main/zeromq: delete the -static subpackage
      main/musl: security fix in i386 math asm (CVE-2019-14697)
      community/sox: fix secfixes comment
      main/linux-rpi: upgrade to 4.19.59
      community/wireguard-rpi: rebuild against kernel 4.19.66-r0
      main/linux-vanilla: upgrade to 4.19.60
      main/linux-vanilla: upgrade to 4.19.62
      main/linux-vanilla: upgrade to 4.19.66
      community/virtualbox-guest-modules-vanilla: rebuild against kernel 4.19.66-r0
      community/wireguard-vanilla: rebuild against kernel 4.19.66-r0
      main/dahdi-linux-vanilla: rebuild against kernel 4.19.66-r0
      main/devicemaster-linux-vanilla: rebuild against kernel 4.19.66-r0
      main/drbd-vanilla: rebuild against kernel 4.19.66-r0
      main/xtables-addons-vanilla: rebuild against kernel 4.19.66-r0
      main/zfs-vanilla: rebuild against kernel 4.19.66-r0
      testing/ipt-netflow-vanilla: rebuild against kernel 4.19.66-r0
      community/go: security upgrade to 1.12.8
      main/linux-vanilla: upgrade to 4.19.67
      community/virtualbox-guest-modules-vanilla: rebuild against kernel 4.19.67-r0
      community/wireguard-vanilla: rebuild against kernel 4.19.67-r0
      main/dahdi-linux-vanilla: rebuild against kernel 4.19.67-r0
      main/devicemaster-linux-vanilla: rebuild against kernel 4.19.67-r0
      main/drbd-vanilla: rebuild against kernel 4.19.67-r0
      main/xtables-addons-vanilla: rebuild against kernel 4.19.67-r0
      main/zfs-vanilla: rebuild against kernel 4.19.67-r0
      testing/ipt-netflow-vanilla: rebuild against kernel 4.19.67-r0
      main/linux-rpi: upgrade to 4.19.67
      community/wireguard-rpi: rebuild against kernel 4.19.67-r0
      main/raspberrypi-bootloader: upgrade to 1.20190718
      ==== release 3.10.2 ====

Rasmus Thomsen (8):
      community/webkit2gtk: upgrade to 2.24.2
      main/ansible: security upgrade to 2.8.3 (CVE-2019-10156)
      community/exempi: security upgrade to 2.5.1
      main/ghostscript: fix CVE-2019-10216
      main/linux-vanilla: Enable CONFIG_SND_HDA_RECONFIG
      main/libmad: fix CVE-2017-8372, CVE-2017-8373, CVE-2017-8374
      main/sdl: fix multiple vulnerabilities
      community/znc: security upgrade to 1.7.4

Timothy Legge (1):
      main/imagemagick: security upgrade to 7.0.8-53

tcely (1):
      community/pdns: add missing schema file


ALPINE LINUX 3.10.1 RELEASED
The Alpine Linux project is pleased to announce the immediate availability of version 3.10.1 of its Alpine Linux operating system.

The full lists of changes can be found in the git log and bug tracker.

GIT SHORTLOG
Andy Postnikov (2):
      community/php7: add argon2 support
      community/php7: upgrade to 7.3.7

Francesco Colista (2):
      main/libvirt: security upgrade to 5.5.0
      community/patchwork: security fix for CVE-2019-13122

Henrik Riomar (1):
      community/intel-ucode: upgrade to 20190618

J0WI (2):
      main/samba: security upgrade to 4.10.5
      community/firefox-esr: security upgrade to 60.7.2 (CVE-2019-11708)

Jake Buchholz (1):
      community/docker: update to 18.09.7

Kevin Daudt (1):
      main/bind: security upgrade to 9.14.3 (CVE-2019-6471)

Milan P. Stanić (3):
      community/mutt: upgrade to 1.12.1
      main/haproxy: upgrade to 2.0.1
      main/postgresql: security upgrade to 11.4

Natanael Copa (32):
      main/py-django: security upgrade to 1.11.21 (CVE-2019-12308)
      main/expat: security upgrade to 2.2.7 (CVE-2018-20843)
      main/irssi: security upgrade to 1.2.1 (CVE-2019-13045)
      main/linux-vanilla: upgrade to 4.19.57
      community/virtualbox-guest-modules-vanilla: rebuild against kernel 4.19.57-r0
      community/wireguard-vanilla: rebuild against kernel 4.19.57-r0
      main/dahdi-linux-vanilla: rebuild against kernel 4.19.57-r0
      main/devicemaster-linux-vanilla: rebuild against kernel 4.19.57-r0
      main/drbd-vanilla: rebuild against kernel 4.19.57-r0
      main/xtables-addons-vanilla: rebuild against kernel 4.19.57-r0
      main/zfs-vanilla: rebuild against kernel 4.19.57-r0
      testing/ipt-netflow-vanilla: rebuild against kernel 4.19.57-r0
      main/linux-rpi: upgrade to 4.19.57
      community/wireguard-rpi: rebuild against kernel 4.19.57-r0
      community/evince: fix CVE-2019-11459
      main/tcpflow: backport fix for CVE-2018-18409
      main/tcpflow: fix secfixes comment
      main/linux-vanilla: upgrade to 4.19.58
      community/virtualbox-guest-modules-vanilla: rebuild against kernel 4.19.58-r0
      community/wireguard-vanilla: rebuild against kernel 4.19.58-r0
      main/dahdi-linux-vanilla: rebuild against kernel 4.19.58-r0
      main/devicemaster-linux-vanilla: rebuild against kernel 4.19.58-r0
      main/drbd-vanilla: rebuild against kernel 4.19.58-r0
      main/xtables-addons-vanilla: rebuild against kernel 4.19.58-r0
      main/zfs-vanilla: rebuild against kernel 4.19.58-r0
      main/linux-rpi: upgrade to 4.19.58
      community/wireguard-rpi: rebuild against kernel 4.19.58-r0
      main/heimdal: security fix for CVE-2019-12098
      main/heimdal: add missing patch
      main/squid: upgrade to 4.8 (CVE-2019-13345)
      main/raspberrypi-bootloader: upgrade to 1.20190620
      ==== relase 3.10.1 ====

Timo Teräs (1):
      main/apk-tools: cherry-pick fix for #10648

Timothy Legge (1):
      main/imagemagick: Fix install location for PerlMagick modules

ntaylor1781 (1):
      main/bzip2: add patch for CVE-2019-12900

prspkt (1):
      community/pdns: security upgrade to 4.1.10



ALPINE LINUX 3.10.0 RELEASED
We are pleased to announce the release of Alpine Linux 3.10.0, the first in the v3.10 stable series.

NEW FEATURES AND NOTEWORTHY NEW PACKAGES
iwd, a modern alternative for wpa_supplicant (EAP is not working yet)
Serial and ethernet support for arm boards
ceph, a distributed object store and filesystem
lightdm, a cross-desktop display manager
SIGNIFICANT UPDATES
Linux 4.19.53
GCC 8.3.0
Busybox 1.30.1
musl libc 1.1.22
LLVM 8.0.0
Go 1.12.6
Python 3.7.3
Perl 5.28.2
Rust 1.34.2
Crystal 0.29.0
PHP 7.3.6
Erlang 22.0.2
Zabbix 4.2.3
Nextcloud 16.0.1
Git 2.22.0
OpenJDK 11.0.4
Xen 4.12.0
Qemu 4.0.0
SIGNIFICANT REMOVALS:
Qt4
Truecrypt
Mongodb
CREDITS
Thanks to everyone sending in patches, bug reports, new and updated aports, and to everyone helping with writing documentation, maintaining the infrastructure, or has contributed in any other way!

Thanks to GIGABYTE, Linode, Fastly, IBM, Packet, vpsFree and RapidSwitch for providing us with hardware and hosting.

CHANGES
The full list of changes can be found in the git log and bug tracker.

COMMIT STATISTICS
    22  Adam Dobrawy
     3  Adam Jensen
     1  Adam Ruzicka
     2  Ain
     1  Aleks Bunin
     2  Alex Laskin
     1  Alex Mirski-Fitton
     7  Alex Raschi
     1  Andrew Bell
    39  André Klitzing
   170  Andy Postnikov
     1  Ariel Zelivansky
     2  Arto Kitula
   127  Bart Ribbers
     1  Bennett Goble
     2  Bjoern Schilberg
     1  Boris Faure
     1  Bradley J Chambers
     6  Bradley Saulteaux
     1  Brian Cole
    53  Carlo Landmeter
     2  Carlos Giraldo
    36  Chloe Kudryavtsev
     1  Chris Topher
     3  Christian Franke
     2  Claas Störtenbecker
     4  Curt Tilmes
     2  DDoSolitary
     1  Daiki Maekawa
     2  Danct12
     3  Daniel Everett
     8  Daniel Isaksen
     3  Daniel Santana
     2  Daniele Debernardi
     1  Dave Hall
     7  Dave Henderson
    21  Dmitry Romanenko
    88  Drew DeVault
     1  Ehud Kaldor
    33  Eivind Uggedal
     5  Eric Molitor
     1  Eugene Pirogov
    57  Fabian Affolter
     5  Fathi Boudra
    11  Fernando Casas Schössow
   478  Francesco Colista
     1  Franck Nijhof
     1  Frank Hunleth
     1  Frédéric Guillot
     1  Fusl
     2  Gareth Williams
     3  Gavin Howard
     8  Gennady Feldman
     1  Guilhem Saurel
     1  Henrik Holst
    78  Henrik Riomar
    12  Holger Jaekel
     6  Ian Bashford
     1  Ian Douglas Scott
     2  Iggy Jackson
     1  Ilya Fedorushkov
   167  J0WI
    17  Jake Buchholz
    47  Jakub Jirutka
     1  Jan Hustak
     5  Jan Tatje
     2  Jason A. Donenfeld
     8  Joe Holden
     1  Joey Smith
     1  Johan Bergström
     1  John Miner
     2  Jonathan Neuschäfer
     4  Julien Reichardt
    19  Kaarle Ritvanen
     7  Karim Kanso
     1  Karol Baraniecki
     1  Keith
    38  Keith Maxwell
     1  Kelvin Nicholson
   206  Kevin Daudt
     1  Konstantin Kulikov
     1  Kopytjuk Marat (CC-AD/PJ-MBB)
     2  Kris Reese
     1  Krzysztof Walo
     1  Kyle Parisi
     1  Laurent Arnoud
    21  Laurent Bercot
   959  Leo
     1  Leo Unglaub
   204  Leonardo Arena
     2  Lex Scarisbrick
     5  Luca Weiss
     6  Lucas Ramage
     2  Lunik
     1  Maciej Klak
     1  Magicloud
     2  Marat Safin
     1  Marcel Haazen
    29  Marian Buschsieweke
     4  Martell Malone
     2  Martin Rusko
     4  Marvin Steadfast
     1  Mateusz Gozdek
     1  Matt Hill
     1  Matt Merhar
     9  Matthias Neugebauer
     2  Michael Davies
     2  Michael Forney
     1  Michael Hamann
     2  Michael Jeanson
     1  Michael Lin
     1  Michael Mason
    53  Mike Sullivan
    84  Milan P. Stanić
     1  Morlay
     1  Mura Li
  1687  Natanael Copa
     3  Nathan Angelacos
     6  Nathan Caldwell
     3  Nathan Johnson
     1  Nick Ashley
     1  Nicola Worthington
    73  Oleg Titov
     3  Oliver Smith
    16  Olliver Schinagl
     3  Orson Teodoro
     1  Oxylibrium
    84  Paul Bredbury
     2  Pavel Demin
     5  Pedro Filipe
     2  Pete Dietl
     2  Peter Kokot
     3  PureTryOut
     2  R4SAS
   220  Rasmus Thomsen
     4  Ricardo F
     2  Richard Mortier
     1  Robert Boisvert
     3  Robert Sacks
     2  Robert Yang
    11  Roberto Oliveira
     6  Russ Webber
     3  Sasha Gerrand
     4  Sergey Safarov
     1  Shem Valentine
    50  Simon Frankenberger
     1  Simone Ripamonti
     2  Steeve Chailloux
     2  Stefan R
     8  Stefan Reiff
     2  Stefan Wagner
     1  Stefan stutz
     1  Stefano Marinelli
     8  Steffen Nurpmeso
    24  Stuart Cardall
     1  Sven Assmann
   120  Sören Tempel
   163  TBK
    20  Taner Tas
     1  Tetsumaki
     2  Thomas Liske
     2  Tiago Ilieve
     6  Tim Brust
     1  Tim Burke
    41  Timo Teräs
    63  Timothy Legge
     1  Tru Huynh
    26  Tuan Hoang
     1  Tyler A
     1  Vladimir Avinkin
     4  William Pitcock
     1  allgdante
    47  alpine-mips-patches
     1  aptalca
     4  iggy
     3  innerspacepilot
     1  inoas
     3  jchipmunk
     1  kpcyrd
     6  nick black
     3  opal hart
     7  ossdev
   531  prspkt
     1  shawrkbait
     1  stf
   149  tcely
     1  vinymeuh
     1  wener
     1  xcko
     1  yangxuan8282


ALPINE LINUX 3.9.4 RELEASED
The Alpine Linux project is pleased to announce the immediate availability of version 3.9.4 of its Alpine Linux operating system.

The full lists of changes can be found in the git log and bug tracker.

GIT SHORTLOG
Andy Postnikov (1):
      community/php7: security upgrade to 7.2.18 (CVE-2019-11036)

Carlo Landmeter (1):
      scripts: add back rpi kernel to armhf

DDoSolitary (1):
      main/linux-vanilla: Enable CONFIG_UEVENT_HELPER for s390x.

Franck Nijhof (1):
      community/lua-resty-http: upgrade to 0.13

Henrik Riomar (8):
      main/wpa_supplicant: fix slow start
      community/pdns-recursor: after entropy
      main/bind: fix slow start
      main/haveged: add missing provide
      main/haveged: more samples in check()
      main/unbound: after entropy
      main/openssh: after entropy
      main/bind: bump pkgrel

J0WI (12):
      community/openjdk7: security upgrade to 7.211.2.6.17
      main/gnutls: upgrade to 3.6.5
      main/gnutls: upgrade to 3.6.6
      main/gnutls: security upgrade to 3.6.7
      main/tzdata: upgrade to 2019a
      main/imagemagick: security upgrade to 7.0.8.38
      main/ldb: upgrade to 1.3.8
      main/samba: security upgrade to 4.8.11
      community/openjdk8: security upgrade to 8.212.04
      community/imagemagick6: security upgrade to 6.9.10-44
      main/imagemagick: security upgrade to 7.0.8-44
      main/dovecot: security upgrade to 2.3.6 (CVE-2019-11494, CVE-2019-11499)

Jakub Jirutka (3):
      main/nginx: upgrade lua-nginx-module to 0.10.15
      main/mariadb: reformat init script
      main/mariadb: fix init script not recognizing started instance

Leo (1):
      main/libpng: upgrade to 1.6.37

Leonardo Arena (11):
      community/nextcloud: upgrade to 15.0.7
      community/webkit2gtk: security upgrade to 2.22.7
      community/php7: security upgrade to 7.2.17
      main/imagemagick: use the upstream source, not a mirror
      main/samba: attempt to fix build on armv7
      main/wpa_supplicant: security fixes
      community/freerdp: security upgrade to 2.0.0_rc4
      main/clamav: security upgrade to 0.100.3
      community/zabbix: upgrade to 4.0.7
      main/freeradius: security fixes (CVE-2019-11234, CVE-2019-11235)
      community/wireshark: security upgrade to 2.6.8

Marcel Haazen (1):
      main/mariadb: replace rpm parameter with datadir parameter

Matt Merhar (1):
      main/haveged: rework init dependencies

Matthias Neugebauer (1):
      main/linux-vanilla: Enable CONFIG_CEPH_LIB_USE_DNS_RESOLVER

Mike Sullivan (1):
      main/linux-vanilla: add commonly used scsi modules for ppc64le

Natanael Copa (37):
      main/libxslt: upgrade to 1.1.33
      main/libxslt: security fix for CVE-2019-11068
      main/bind: security upgrade to 9.12.4_p1 (CVE-2018-5743,CVE-2019-6467)
      main/bind: fix build on non-x86
      community/shadow: fix conflict with util-linux-doc and coreutils-doc
      main/linux-vanilla: upgrade to 4.19.36
      main/linux-vanilla: enable Realtek RTL8822BE driver
      main/linux-vanilla: upgrade to 4.19.40
      community/virtualbox-guest-modules-vanilla: rebuild against kernel 4.19.40-r0
      main/dahdi-linux-vanilla: rebuild against kernel 4.19.40-r0
      main/devicemaster-linux-vanilla: rebuild against kernel 4.19.40-r0
      main/drbd9-vanilla: rebuild against kernel 4.19.40-r0
      main/xtables-addons-vanilla: rebuild against kernel 4.19.40-r0
      main/spl-vanilla: rebuild against kernel 4.19.40-r0
      main/zfs-vanilla: rebuild against kernel 4.19.40-r0
      main/linux-rpi: upgrade to 4.19.40
      community/znc: security fix for CVE-2019-9917
      main/mercurial: security upgrade to 4.9.1 (CVE-2019-3902)
      main/file: security upgrade to 5.36
      main/strongswan: enable aesni on x86_64
      main/lua5.3: security fix for CVE-2019-6706
      main/ruby: security upgrade to 2.5.5
      main/ruby: fix secfixes comment
      main/python2: sec upgrade to 2.7.16 (CVE-2018-14647)
      main/python2: security fixes (CVE-2019-9636, CVE-2019-9948)
      main/nginx: disable lua-nginx-module on s390x
      main/linux-vanilla: upgrade to 4.19.41
      community/virtualbox-guest-modules-vanilla: rebuild against kernel 4.19.41-r0
      main/dahdi-linux-vanilla: rebuild against kernel 4.19.41-r0
      main/devicemaster-linux-vanilla: rebuild against kernel 4.19.41-r0
      main/drbd9-vanilla: rebuild against kernel 4.19.41-r0
      main/spl-vanilla: rebuild against kernel 4.19.41-r0
      main/xtables-addons-vanilla: rebuild against kernel 4.19.41-r0
      main/zfs-vanilla: rebuild against kernel 4.19.41-r0
      main/linux-rpi: upgrade to 4.19.41
      main/raspberrypi-bootloader: upgrade to 1.20190401
      ==== release 3.9.4 ====

Richard Mortier (1):
      main/alpine-conf: fix invocation of `openssl` when listing ciphers

Thomas Liske (1):
      main/linux-vanilla: enable ipset set type hash:ip,mac

Timo Teräs (9):
      main/linux-firmware: upgrade to 20190322, update rpi firmwares
      main/alpine-conf: include associated firmware files to modloop
      scripts/mkimg.arm.sh: remove manual (now redundant) clm_blob spec
      community/perl-test-nginx: backport from edge
      community/lua-resty-string: backport from edge
      community/lua-resty-hmac: backport from edge
      community/lua-resty-session: backport from edge
      community/lua-resty-jwt: backport from edge
      community/lua-resty-openidc: backport from edge

Tuan Hoang (1):
      main/linux-vanilla: remove KERNEL_NOBP on s390x

alpine-mips-patches (1):
      main/libsndfile: update CVE-2018-19758 fix from upstream

prspkt (1):
      community/flatpak: security upgrade to 1.0.8

tcely (5):
      main/bind: security upgrade to 9.12.3-P4
      Revert "main/bind: security upgrade to 9.12.3-P4"
      main/bind: security upgrade to 9.12.3_p4
      main/bind: bump pkgrel for reverted commit
      main/py3-ply: new aport


ALPINE LINUX 3.9.3 RELEASED
The Alpine Linux project is pleased to announce the immediate availability of version 3.9.3 of its Alpine Linux operating system.

The full lists of changes can be found in the git log and bug tracker.

GIT SHORTLOG
André Klitzing (1):
      community/flatpak: security upgrade to 1.0.7

Carlo Landmeter (2):
      main/mesa: armv7 add vc4 support
      scripts: add rpi2 kernel to armhf release

Francesco Colista (5):
      main/openjpeg: security fixes
      community/wireshark: security upgrade to 2.6.7
      community/phpmyadmin: security fixes
      main/libssh2: security upgrade to 1.8.1
      community/drupal7: security upgrade to 7.65

Henrik Riomar (1):
      main/zfs: import pool before swap

J0WI (9):
      community/openjdk8: security upgrade to 3.11.0 (java 8u201b08)
      main/openssl: upgrade to 1.1.1b
      main/openssl: security update to patch CVE-2019-1543
      main/dovecot: security upgrade to 2.3.5.1
      main/apache2: security upgrade to 2.4.39
      community/mumble: security fixes (CVE-2018-20743)
      main/ghostscript: security fixes (CVE-2019-3835, CVE-2019-3838, CVE-2019-6116)
      community/imagemagick6: security upgrade to 6.9.10.37
      main/gd: modernize and add security patches

Jakub Jirutka (3):
      community/alpine-make-rootfs: upgrade to 0.3.0
      community/openjdk8: add missing nss dependency
      main/opensmtpd: fix init script, missing extra_commands

Kaarle Ritvanen (2):
      main/dmvpn: upgrade to 1.0.2
      main/aconf: upgrade to 0.7.1

Leonardo Arena (7):
      community/chromium: security upgrade to 72.0.3626.121 (CVE-2019-5786)
      main/postgresql: upgrade to 11.2
      community/imagemagick6: upgrade to 6.9.10.39
      main/wget: security upgrade to 1.20.3 (CVE-2019-5953)
      main/putty: security upgrade to 0.71
      main/putty: on arm* and aarch64 needs linux-headers
      main/gd: disable tests for more arches

Mike Sullivan (1):
      main/linux-vanilla: enable CONFIG_CRYPTO_USER config settings fix checksum for config-vanilla.ppc64le

Natanael Copa (55):
      main/abuild: upgrade to 3.3.1
      main/linux-vanilla: enable crypto lz4* for armhf and ppc64le
      main/linux-vanilla: enable crypto zstd for all arches
      main/linux-vanilla: add function for oldconfig
      main/linux-vanilla: upgrade to 4.19.28
      community/virtualbox-guest-modules-vanilla: rebuild against kernel 4.19.28-r0
      main/dahdi-linux-vanilla: rebuild against kernel 4.19.28-r0
      main/devicemaster-linux-vanilla: rebuild against kernel 4.19.28-r0
      main/drbd9-vanilla: rebuild against kernel 4.19.28-r0
      main/spl-vanilla: rebuild against kernel 4.19.28-r0
      main/xtables-addons-vanilla: rebuild against kernel 4.19.28-r0
      main/zfs-vanilla: rebuild against kernel 4.19.28-r0
      main/linux-rpi: upgrade to 4.19.28
      main/linux-vanilla: upgrade to 4.19.29
      main/linux-rpi: upgrade to 4.19.29
      community/virtualbox-guest-modules-vanilla: rebuild against kernel 4.19.29-r0
      main/dahdi-linux-vanilla: rebuild against kernel 4.19.29-r0
      main/devicemaster-linux-vanilla: rebuild against kernel 4.19.29-r0
      main/drbd9-vanilla: rebuild against kernel 4.19.29-r0
      main/spl-vanilla: rebuild against kernel 4.19.29-r0
      main/xtables-addons-vanilla: rebuild against kernel 4.19.29-r0
      main/zfs-vanilla: rebuild against kernel 4.19.29-r0
      testing/ipt-netflow-vanilla: rebuild against kernel 4.19.29-r0
      testing/wireguard-vanilla: rebuild against kernel 4.19.29-r0
      testing/wireguard-virt: rebuild against kernel 4.19.29-r0
      main/libssh2: upgrade to 1.8.2
      main/linux-vanilla: upgrade to 4.19.30
      main/linux-rpi: upgrade to 4.19.30
      main/linux-rpi: upgrade to 4.19.33
      main/linux-vanilla: upgrade to 4.19.33
      community/virtualbox-guest-modules-vanilla: rebuild against kernel 4.19.33-r0
      main/dahdi-linux-vanilla: rebuild against kernel 4.19.33-r0
      main/devicemaster-linux-vanilla: rebuild against kernel 4.19.33-r0
      main/drbd9-vanilla: rebuild against kernel 4.19.33-r0
      main/spl-vanilla: rebuild against kernel 4.19.33-r0
      main/xtables-addons-vanilla: rebuild against kernel 4.19.33-r0
      main/zfs-vanilla: rebuild against kernel 4.19.33-r0
      testing/ipt-netflow-vanilla: rebuild against kernel 4.19.33-r0
      testing/wireguard-vanilla: rebuild against kernel 4.19.33-r0
      testing/wireguard-virt: rebuild against kernel 4.19.33-r0
      main/linux-vanilla: upgrade to 4.19.34
      community/virtualbox-guest-modules-vanilla: rebuild against kernel 4.19.34-r0
      main/dahdi-linux-vanilla: rebuild against kernel 4.19.34-r0
      main/devicemaster-linux-vanilla: rebuild against kernel 4.19.34-r0
      main/drbd9-vanilla: rebuild against kernel 4.19.34-r0
      main/spl-vanilla: rebuild against kernel 4.19.34-r0
      main/xtables-addons-vanilla: rebuild against kernel 4.19.34-r0
      main/zfs-vanilla: rebuild against kernel 4.19.34-r0
      testing/ipt-netflow-vanilla: rebuild against kernel 4.19.34-r0
      testing/wireguard-vanilla: rebuild against kernel 4.19.34-r0
      testing/wireguard-virt: rebuild against kernel 4.19.34-r0
      main/linux-rpi: upgrade to 4.19.34
      main/gcc: upgrade to 8.3.0
      main/python3: rebuild with gcc 8.3.0
      ==== release 3.9.3 ====

Simon Frankenberger (1):
      community/bareos: Fix segfaults on startup

Sören Tempel (3):
      community/firefox-esr: upgrade to 60.5.0
      community/firefox-esr: upgrade to 60.5.2
      community/firefox-esr: upgrade to 60.6.1

Tuan Hoang (3):
      main/musl: correct FADV macro on s390x
      main/strace: fix SIGNAL_FRAMESIZE on s390x
      main/linux-vanilla: add pkey for s390x

prspkt (1):
      community/pdns: security upgrade to 4.1.7



ALPINE LINUX 3.9.2 RELEASED
The Alpine Linux project is pleased to announce the immediate availability of version 3.9.2 of its Alpine Linux operating system.

This is a bugfix release of the v3.9 stable branch, which fixes a regression introduced in 3.9.1 that caused setup-alpine to break.

The full lists of changes can be found in the git log and bug tracker.

GIT SHORTLOG
Carlo Landmeter (1):
      drone: x86 set correct personality

Leonardo Arena (2):
      main/openssh: security fixes
      main/openssh: include patch from upstream

Natanael Copa (2):
      scripts/mkimg.base.sh: replace libressl with openssl
      ==== release 3.9.2 ====

ALPINE LINUX 3.9.1 RELEASED
The Alpine Linux project is pleased to announce the immediate availability of version 3.9.1 of its Alpine Linux operating system.

This is a bugfix release of the v3.9 stable branch, based on linux-4.19.26 kernels and it contains bugfixes.

The full lists of changes can be found in the git log and bug tracker.

GIT SHORTLOG
Adam Ruzicka (1):
      community/borgbackup: backport patch to make borg work again

Alex Mirski-Fitton (1):
      main/openssl: Fix openssl secfix version number

Bwko (1):
      community/gitea: security upgrade to 1.6.4

Carlo Landmeter (5):
      main/raspberrypi-bootloader: upgrade to 1.20181112
      main/lxc: fix CVE-2019-5736
      main/cyrus-sasl: add missing /etc/sasl2 to libsasl2
      drone: add config for v3.9
      scripts: add modloopfw support

DDoSolitary (1):
      main/linux-vanilla: Enable CONFIG_HW_RANDOM_VIRTIO for ppc64le

Drew DeVault (1):
      main/py-werkzeug: update to 0.14.1

Francesco Colista (2):
      community/py-sip: fixed the build for PyQt5.sip and sip binary
      community/gns3-gui: fixed sip-qt5 error dependency

Gennady Feldman (1):
      main/linux-vanilla: Don't build VBOXGUEST module.

J0WI (5):
      main/ghostscript: security update for CVE-2019-6116
      main/dnssec-root: rebuild against openssl
      main/tar: upgrade to 1.32
      main/mariadb: security upgrade to 10.3.13
      community/tor: security upgrade to 0.3.4.11

Jake Buchholz (1):
      community/runc: upgrade for CVE-2019-5736

Jakub Jirutka (1):
      community/elasticsearch: upgrade to 6.4.3

Joe Holden (2):
      main/linux-vanilla: build CONFIG_RTL8723BS=m
      main/linux-vanilla: enable CONFIG_PINCTRL_BAYTRAIL=y

Kaarle Ritvanen (3):
      main/apache2: fix mod_proxy default configuration
      main/dmvpn: upgrade to 1.0.1
      main/aconf: upgrade to 0.7.0

Leonardo Arena (9):
      main/spice: security fix (CVE-2019-3813)
      main/spice: temporarily disable tests
      main/spice: re-enable tests
      main/wavpack: security fixes (CVE-2018-19840, CVE-2018-19841)
      community/libraw: security upgrade to 0.19.2
      main/dovecot: disable tests on 32bit arches
      community/nextcloud: upgrade to 15.0.4
      community/zabbix: upgrade to 4.0.5
      community/nextcloud: upgrade to 15.0.5

Milan P. Stanić (2):
      main/libxml2: fix null pointer dereference
      main/curl: fix segfault when running cargo

Natanael Copa (52):
      main/wireless-regdb: move from community
      main/alpine-conf: backport support for modloopfw option
      community/chromium: upgrade to 72.0.3626.109 and fix deadlock
      community/chromium: fix build on armv7
      main/abuild: backport support for pcprefix
      main/qemu: workaround bug in qemu due to memcpy assumed to be atomic
      main/tinyproxy: fix conf location and openrc script
      main/libressl: upgrade to 2.7.5 and set pcprefix
      main/linux-rpi: upgrade to 4.19.25
      main/linux-vanilla: upgrade to 4.19.20
      main/linux-vanilla: upgrade to 4.19.21
      main/linux-vanilla: enable MMC_SDHCI_XENON for aarch64
      main/linux-vanilla: upgrade to 4.19.25
      community/virtualbox-guest-modules-vanilla: rebuild against kernel 4.19.25-r0
      main/dahdi-linux-vanilla: rebuild against kernel 4.19.25-r0
      main/devicemaster-linux-vanilla: rebuild against kernel 4.19.25-r0
      main/drbd9-vanilla: rebuild against kernel 4.19.25-r0
      main/spl-vanilla: rebuild against kernel 4.19.25-r0
      main/xtables-addons-vanilla: rebuild against kernel 4.19.25-r0
      main/zfs-vanilla: rebuild against kernel 4.19.25-r0
      testing/ipt-netflow-vanilla: rebuild against kernel 4.19.25-r0
      testing/wireguard-vanilla: rebuild against kernel 4.19.25-r0
      testing/wireguard-virt: rebuild against kernel 4.19.25-r0
      main/mkinitfs: upgrade to 3.4.1
      main/dnssec-root: upgrade to 20190225 and make reproducible
      main/py-django: security upgrade to 1.11.20 (CVE-2019-6975)
      main/knock: backport fix for uninitialized tcpflags
      community/qt5-qtwayland: clean up depends
      main/linux-vanilla: upgrade to 4.19.26
      main/linux-rpi: upgrade to 4.19.26
      community/virtualbox-guest-modules-vanilla: rebuild against kernel 4.19.26-r0
      main/dahdi-linux-vanilla: rebuild against kernel 4.19.26-r0
      main/devicemaster-linux-vanilla: rebuild against kernel 4.19.26-r0
      main/drbd9-vanilla: rebuild against kernel 4.19.26-r0
      main/spl-vanilla: rebuild against kernel 4.19.26-r0
      main/xtables-addons-vanilla: rebuild against kernel 4.19.26-r0
      main/zfs-vanilla: rebuild against kernel 4.19.26-r0
      testing/ipt-netflow-vanilla: rebuild against kernel 4.19.26-r0
      testing/wireguard-vanilla: rebuild against kernel 4.19.26-r0
      testing/wireguard-virt: rebuild against kernel 4.19.26-r0
      scripts/genrootfs.sh: make sure root login is disabled
      scripts/mkimg.arm.sh: create rpi image for armv7
      scripts: generate grub efi for arm except rpi
      scripts/genrootfs.sh: exclude dev/*
      main/hylafax: fix secfixes comment
      main/lame: fix secfixes comment
      main/ldns: fix secfixes comment
      main/libexif: fix secfixes comment
      main/libxfont: fix secfixes comment
      main/cabextract: fix secfixes comment
      main/raspberrypi-bootloader: upgrade to 1.20190215
      ==== release 3.9.2 ====

Olliver Schinagl (1):
      scripts: add armv7 support to images

Pavel Demin (2):
      main/gpsd: fix PPS functionality
      main/gpsd: bump pkgrel

PureTryOut (1):
      community/qt5-qtwayland: new aport

Simon Frankenberger (6):
      community/openjdk7: security upgrade to 7.201.2.6.16
      main/dovecot: Security upgrade to 2.3.4.1 (CVE-2019-3814)
      main/mosquitto: Fix for CVE-2018-12546, CVE-2018-12550, CVE-2018-12551
      main/apache2: Create /run folder for apache2 on install
      community/wxgtk: Rebuild due to incompatibilities
      main/curl: Security upgrade to 7.64.0

Sören Tempel (1):
      main/libvorbis: Fix CVE-2018-10393

Timo Teräs (5):
      main/mkinitfs: fix fbsplash
      community/omxplayer: upgrade to snapshot of 2019-01-02
      main/alpine-conf: include wifi regulatory db in modloop
      community/wireless-regdb: include the new format firmware file
      scripts/mkimg.base.sh: include wifi regulatory database in modloop

Tuan Hoang (1):
      main/fuse3: move fuse.conf to correct directory

ALPINE LINUX 3.9.0 RELEASED
We are pleased to announce the release of Alpine Linux 3.9.0, the first in the v3.9 stable series.

NEW FEATURES AND NOTEWORTHY NEW PACKAGES
Support for armv7
Switch from LibreSSL to OpenSSL
Modloop is now being signed
Improved GRUB support. GRUB users should check if their config is generated correctly and have emergency boot media prepared
SIGNIFICANT UPDATES
Linux 4.19
GCC 8.2.0
Busybox 1.29
musl libc 1.1.20
Go 1.11.5
LXC 3.1
PostgreSQL 11.1
Node.js 10.14.2
Crystal 0.27
Zabbix 4.0.3
Nextcloud 15.0.2
NOTEWORTHY REMOVALS
Firefox is only available on x86_64 due to Rust.
CREDITS
Thanks to everyone sending in patches, bug reports, new and updated aports, and to everyone helping with writing documentation, maintaining the infrastructure, or has contributed in any other way!

Thanks to GIGABYTE, Scaleway, Fastly, IBM, Packet, vpsFree and RapidSwitch for providing us with hardware and hosting.

CHANGES
The full list of changes can be found in the git log and bug tracker.

COMMIT STATISTICS
     1  AdamRushad
     6  Ain
    10  Alex Raschi
    17  Alexander Edland
     1  Alexandre Oliveira
     1  Anatoly Kamchatnov
     1  Andrzej Trzaska
    66  André Klitzing
     1  Andy Li
   263  Andy Postnikov
     1  Anil Madhavapeddy
     4  Arthur Jones
     7  Bart Ribbers
     1  Bernhard J. M. Gruen
     2  Bjoern Schilberg
     1  Brad Fritz
     1  Brian Kubisiak
     3  Bwko
     1  Carl Kittelberger
   178  Carlo Landmeter
     5  Chloe Kudryavtsev
    16  Curt Tilmes
     1  Cág
     2  Daniel Beal
    14  Daniel Isaksen
     1  Daniele Debernardi
     1  Dario Ernst
     4  Dave Henderson
     1  David Lutterkort
     1  Dawid Dziurla
    14  Dmitry Romanenko
    33  Drew DeVault
     1  Dustin Heimerl
     2  Erik Ogan
     1  Euan Harris
     4  Eugene Pirogov
    82  Fabian Affolter
     1  Filippo Valsorda
   247  Francesco Colista
     3  Frank Hunleth
     1  Fusl
     9  Gennady Feldman
     1  Governikus
     1  Grant Miller
     4  He Yangxuan
     1  Henrik Holst
     2  Henrik Nilsson
    46  Henrik Riomar
     2  Hidde van der Heide
     1  Hiroshi Kajisha
     8  Holger Jaekel
     1  Ian Bashford
     1  Ian Douglas Scott
     2  Ivan Tham
   107  J0WI
    16  Jake Buchholz
   262  Jakub Jirutka
     1  James White
     4  Jan Tatje
    13  Jason A. Donenfeld
     3  Jean-Louis Fuchs
     3  Joe Groocock
     4  Joe Holden
     1  John Coyle
     4  Jonathan Neuschäfer
     1  Jose Maria Garcia
     1  Josef Fröhle
     1  Julen Landa Alustiza
     1  Julien Reichardt
    53  Kaarle Ritvanen
     1  Katie Holly
     8  Keith Maxwell
    30  Kevin Daudt
     1  Kory Prince
     1  Kyle Parisi
     8  Laurent Bercot
   237  Leonardo Arena
     7  Linux User
     1  Louis
     1  Lovell Fuller
     3  Luca Weiss
     5  Lucas Ramage
     3  Marat Safin
     8  Marc Vertes
    29  Marian Buschsieweke
     1  Markus Heimbach
     4  Marvin Steadfast
     1  Mathias De Maré
     1  Matteo Gazzetta
     1  Michael De La Rue
     1  Michael Hamann
     2  Michael Lin
     1  Michael Mason
     2  Michael Truog
     1  Michael Wyraz
     3  Michal Sidor (Michcioperz)
     1  Mike Bland
     1  Mike Crute
     2  Mike Milner
    50  Mike Sullivan
     1  Mikhail Ivko
    20  Milan P. Stanić
     3  Mobile Stream
     3  Mohammed Sadiq
  1513  Natanael Copa
     2  Nathan Angelacos
     3  Nathan Caldwell
     2  Nathan Johnson
     1  Niclas Kroon
     1  Nils Andreas Svee
    11  Oleg Titov
     4  Oliver Smith
    10  Paul Bredbury
     4  Paul Morgan
     1  Pavlo Khudolieiev
     1  Paweł Tomak
    43  Pedro Filipe
     1  Peter Kokot
     1  Philippe Schommers
     1  PureTryOut
     2  Richard Mortier
     1  Rick Chen
     1  Robert Hencke
     3  Robert Yang
   325  Roberto Oliveira
     1  Rostyslav Fridman
    29  Sascha Paunovic
     1  Sergey Kuritsin
     1  Sergey Safarov
     6  Shiz
    19  Simon Frankenberger
     1  Stefan Schwarz
    17  Stefan Wagner
     4  Steffen Nurpmeso
     2  Steve HOLWEG
    34  Stuart Cardall
   152  Sören Tempel
    36  TBK
    32  Taner Tas
     2  Ted Trask
     1  Terror
     1  Thomas Eizinger
     1  Thomas Liske
    10  Tiago Ilieve
     1  Tianon Gravi
     6  Tim Brust
    85  Timo Teräs
     3  Tuan Hoang
     1  Tuan M. Hoang
     5  Valery Kartel
     2  Vince Mele
     1  Vitaly Aminev
    15  William Pitcock
     1  Wojciech Górski
     1  Your Name
     1  ageekymonk
     1  allgdante
    68  alpine-mips-patches
     2  emersion
    57  info@mobile-stream.com
     4  jchipmunk
     1  khm
     1  liluo
     1  midipix
     1  nervo
     1  noname
     4  opal hart
   401  prspkt
     4  raschi.alex@gmail.com
     2  ryang
    27  tcely
     1  tmpfile
     2  wener
     1  wenerme
     1  yangxuan8282
     1  zelivans


ALPINE LINUX 3.8.2 RELEASED
The Alpine Linux project is pleased to announce the immediate availability of version 3.8.2 of its Alpine Linux operating system.

This is a bugfix release of the v3.8 stable branch, based on linux-4.14.89 kernels and it contains bugfixes.

The full lists of changes can be found in the git log and bug tracker.

GIT SHORTLOG
Andy Postnikov (11):
      community/php7: security upgrade to 7.2.10
      main/apache2: security upgrade to 2.4.35 (CVE-2018-11763)
      main/icecast: security upgrade to 2.4.4 (CVE-2018-18820)
      main/nginx: security upgrade to 1.14.1
      main/ghostscript: security upgrade to 9.26 (CVE-2018-19409)
      main/lighttpd: upgrade to 1.4.52
      community/php7: security upgrade to 7.2.13
      community/php5: security upgrade to 5.6.38 (CVE-2018-17082)
      community/php5: backport dependency fixes from edge
      main/nginx: upgrade to 1.14.2
      community/php5: security upgrade to 5.6.39

Carlo Landmeter (3):
      main/dnsmasq: add BRIDGE_ADDR_EXTRA support to initd
      main/mqtt-exec: initd use supervise-daemon
      main/mqtt-exec: keep exec_user for backwards compatibility

Euan Harris (1):
      main/libjpeg-turbo: Backport fix for CVE-2018-1152

Fabian Affolter (1):
      main/py-requests: upgrade to 2.19.1

Henrik Riomar (3):
      main/nfs-utils: drop build dep on libnfsidmap-dev
      main/xen: upgrade to 4.10.2
      main/open-vm-tools: fix reboot and halt

Ian Douglas Scott (1):
      main/gcc: patch to remove call to glibc-specific function in Ada library

J0WI (4):
      community/openjdk8: security upgrade to 3.9.0 (java 8u181b13)
      main/openssl: security upgrade to 1.0.2q - CVE-2018-0734 - CVE-2018-5407
      main/clamav: security upgrade to 0.100.2
      main/ghostscript: security fixes (CVE-2018-17961, CVE-2018-18073, CVE-2018-18284)

Jake Buchholz (1):
      main/linux-vanilla: enable NFS v4.1 & v4.2

Jakub Jirutka (7):
      community/lua-http: fix wrong depend on lua5.[12]-compat5.3
      main/ruby: security upgrade to 2.5.2
      main/one-context: upgrade to 0.5.5
      main/nodejs: security upgrade to 8.14.0
      main/nginx: upgrade module http-fancyindex to v0.4.3
      main/nginx: upgrade module http-lua to 0.10.13
      main/nginx: upgrade module http-vod to 1.24

Jean-Louis Fuchs (1):
      main/duplicity: missing pkgrel bump

Kaarle Ritvanen (10):
      main/lua-ossl: support encrypted keys
      main/lua-asn1: upgrade to 2.2.0
      main/strongswan: increase guard time
      main/tunnel: backport from edge
      main/dmvpn: backport from edge
      main/dmvpn: upgrade to 1.0.0
      main/py-django-haystack: fix dependencies
      main/mariadb-c-connector: fix socket path
      main/awall: upgrade to 1.5.2
      main/busybox: do not hang on DAD failure

Leonardo Arena (20):
      main/libsndfile: security fix (CVE-2018-13139)
      main/ulogd; fix patch and checksum
      main/strongswan: security fix (CVE-2018-17540)
      main/libexif: security fix (CVE-2017-7544)
      main/hylafax: security fix (CVE-2018-17141)
      community/nextcloud: upgrade to 13.0.7
      community/ffmpeg: use built-in RTMP support
      main/dnsmasq: fix typo
      main/curl: security fixes
      main/tiff: security fixes
      main/pango: security fix (CVE-2018-15120)
      main/lcms2: security fix (CVE-2018-16435)
      main/ghostscript: security upgrade to 9.25 (CVE-2018-16802)
      main/spice: security upgrade to 0.14.1 (CVE-2018-10873)
      main/spice-protocol: upgrade to 0.12.14
      community/zabbix: upgrade to 3.4.15
      community/postgresql-bdr-extension0.9: downgrade to 0.9.0 to maintain compatibility with earlier Alpine versions
      community/nextcloud: upgrade 13.0.8
      community/nextcloud: upgrade to 14.0.4
      community/nextcloud: additional apps are required to run upon installation of main package

Markus Heimbach (1):
      main/postfix: Adding missing m4 build dependency

Marvin Steadfast (1):
      main/libssh: security upgrade 0.7.6 - CVE-2018-10933

Natanael Copa (113):
      main/libjpeg-turbo: backport security fix (CVE-2018-11813)
      main/openssl1.0: upgrade to 1.0.2p
      main/libnfsidmap: remove due to merge with nfs-utils
      community/webkit2gtk: security upgrade to 2.20.4
      community/libreoffice: fix tread stack size issue
      main/strongswan: backport security fix (CVE-2018-16151, CVE-2018-16152)
      main/strongswan: bump pkgrel
      main/nss: backport fix for CVE-2018-12384
      main/gd: backport security fix for CVE-2018-1000222
      main/libx11: security upgrade to 1.6.6
      main/hylafax: fix secfixes comment
      main/libexif: fix secfixes comment
      main/tzdata: upgrade to 2018f
      main/libxml2: backport security fixes
      main/git: security upgrade to 2.18.1 (CVE-2018-17456)
      community/wireshark: security upgrade to 2.4.10
      main/xorg-server: security fix (CVE-2018-14665)
      main/rp-pppoe: update pkgdesc
      main/db: add secfixes comment for unaffected CVEs
      community/go: upgrade to 1.10.5
      main/linux-vanilla: upgrade to 4.14.73
      main/linux-vanilla: upgrade to 4.14.78
      main/linux-vanilla: enable drivers for Huawei Taishan 2280
      main/linux-vanilla: upgrade to 4.14.81
      main/linux-vanilla: upgrade to 4.14.82
      main/linux-rpi: upgrade to 4.14.82
      community/virtualbox-guest-modules-vanilla: rebuild against kernel 4.14.82-r0
      main/dahdi-linux-vanilla: rebuild against kernel 4.14.82-r0
      main/devicemaster-linux-vanilla: rebuild against kernel 4.14.82-r0
      main/drbd9-vanilla: rebuild against kernel 4.14.82-r0
      main/spl-vanilla: rebuild against kernel 4.14.82-r0
      main/xtables-addons-vanilla: rebuild against kernel 4.14.82-r0
      main/zfs-vanilla: rebuild against kernel 4.14.82-r0
      testing/aws-ena-driver-vanilla: rebuild against kernel 4.14.82-r0
      testing/ipt-netflow-vanilla: rebuild against kernel 4.14.82-r0
      testing/wireguard-vanilla: rebuild against kernel 4.14.82-r0
      main/imagemagick: disable openmp
      main/pango: fix secfixes comment
      main/openjpeg: security fixes (CVE-2017-17480,CVE-2018-18088)
      main/libmspack: security upgrade to 0.8_alpha
      community/salt: security upgrade to 2018.3.3 (CVE-2018-15750,CVE-2018-15751)
      community/salt: add secfixes comment
      main/cabextract: security upgrade to 1.9 (CVE-2018-18584)
      main/cabextract: fix secfixes comment
      main/linux-vanilla: upgrade to 4.14.84
      community/virtualbox-guest-modules-vanilla: rebuild against kernel 4.14.84-r0
      main/dahdi-linux-vanilla: rebuild against kernel 4.14.84-r0
      main/devicemaster-linux-vanilla: rebuild against kernel 4.14.84-r0
      main/drbd9-vanilla: rebuild against kernel 4.14.84-r0
      main/spl-vanilla: rebuild against kernel 4.14.84-r0
      main/xtables-addons-vanilla: rebuild against kernel 4.14.84-r0
      main/zfs-vanilla: rebuild against kernel 4.14.84-r0
      testing/aws-ena-driver-vanilla: rebuild against kernel 4.14.84-r0
      testing/ipt-netflow-vanilla: rebuild against kernel 4.14.84-r0
      testing/wireguard-vanilla: rebuild against kernel 4.14.84-r0
      main/linux-rpi: upgrade to 4.14.84
      main/git: security fix (CVE-2018-19486)
      community/roundcubemail: security upgrade to 1.3.8 (CVE-2018-19206)
      main/bind: security upgrade to 9.12.3 (CVE-2018-5741)
      main/lua5.3: upgrade to 5.3.5
      main/lua5.3: fix linenoise patch
      main/libao: security fix for CVE-2017-11548
      main/perl: security upgrade to 5.26.3
      main/linux-vanilla: upgrade to 4.14.85
      community/virtualbox-guest-modules-vanilla: rebuild against kernel 4.14.85-r0
      main/dahdi-linux-vanilla: rebuild against kernel 4.14.85-r0
      main/devicemaster-linux-vanilla: rebuild against kernel 4.14.85-r0
      main/drbd9-vanilla: rebuild against kernel 4.14.85-r0
      main/spl-vanilla: rebuild against kernel 4.14.85-r0
      main/xtables-addons-vanilla: rebuild against kernel 4.14.85-r0
      main/zfs-vanilla: rebuild against kernel 4.14.85-r0
      testing/aws-ena-driver-vanilla: rebuild against kernel 4.14.85-r0
      testing/ipt-netflow-vanilla: rebuild against kernel 4.14.85-r0
      testing/wireguard-vanilla: rebuild against kernel 4.14.85-r0
      main/linux-rpi: upgrade to 4.14.85
      community/jenkins: upgrade to 2.121.3
      main/ghostscript: update secfixes comment
      main/tiff: security upgrade to 4.0.10
      main/openrc: fix hostname script
      commit/php7: fix merge error
      main/linux-vanilla: upgrade to 4.14.88
      community/virtualbox-guest-modules-vanilla: rebuild against kernel 4.14.88-r0
      main/dahdi-linux-vanilla: rebuild against kernel 4.14.88-r0
      main/devicemaster-linux-vanilla: rebuild against kernel 4.14.88-r0
      main/drbd9-vanilla: rebuild against kernel 4.14.88-r0
      main/spl-vanilla: rebuild against kernel 4.14.88-r0
      main/xtables-addons-vanilla: rebuild against kernel 4.14.88-r0
      main/zfs-vanilla: rebuild against kernel 4.14.88-r0
      testing/aws-ena-driver-vanilla: rebuild against kernel 4.14.88-r0
      testing/ipt-netflow-vanilla: rebuild against kernel 4.14.88-r0
      testing/wireguard-vanilla: rebuild against kernel 4.14.88-r0
      main/linux-rpi: upgrade to 4.14.88
      community/go: upgrade to 1.10.7
      main/linux-vanilla: upgrade to 4.14.89
      community/virtualbox-guest-modules-vanilla: rebuild against kernel 4.14.89-r0
      main/dahdi-linux-vanilla: rebuild against kernel 4.14.89-r0
      main/devicemaster-linux-vanilla: rebuild against kernel 4.14.89-r0
      main/drbd9-vanilla: rebuild against kernel 4.14.89-r0
      main/spl-vanilla: rebuild against kernel 4.14.89-r0
      main/xtables-addons-vanilla: rebuild against kernel 4.14.89-r0
      main/zfs-vanilla: rebuild against kernel 4.14.89-r0
      testing/aws-ena-driver-vanilla: rebuild against kernel 4.14.89-r0
      testing/ipt-netflow-vanilla: rebuild against kernel 4.14.89-r0
      testing/wireguard-vanilla: rebuild against kernel 4.14.89-r0
      main/linux-rpi: upgrade to 4.14.89
      main/varnish: upgrade to 6.0.2
      community/pdns-recursor: security upgrade to 4.1.8
      main/py-packaging: move from community due to py-sphinx
      main/samba: security upgrade to 4.8.8
      main/py-sphinx: add all runtime deps to makedepends
      community/cfengine: fix needed symlinks
      main/imagemagick: upgrade to 7.0.7.39
      ==== release 3.8.2 ====

Roberto Oliveira (2):
      community/keepalived: upgrade to 2.0.5
      main/py-typing: move from community

Thomas Liske (1):
      main/ipset: fix reloading of existing ipsets

Timo Teräs (1):
      main/asterisk: security upgrade to 15.6.1

raschi.alex@gmail.com (1):
      community/gst-plugins-bad: enable opus support
