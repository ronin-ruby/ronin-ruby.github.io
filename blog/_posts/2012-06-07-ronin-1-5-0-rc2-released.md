---
layout: post
title:
  ronin-support 0.5.0.rc2, ronin 1.5.0.rc2, ronin-gen 1.2.0.rc2 released
author: postmodern
tags:
  - prerelease
  - ronin-support
  - ronin
---

[ronin-support 0.5.0.rc2][1], [ronin 1.5.0.rc2][2] and [ronin-gen 1.2.0.rc2][3] 
have been released.

    $ gem install ronin-support ronin ronin-gen --pre

### Checksums

* `ronin-support-0.5.0.rc2.gem`
  * **MD5:** `f6e8039f25723612ffc634d1c6ca0854`
  * **SHA1:** `14df56b762b4a8a2439551e638b76c9a6375adde`
  * [PGP][4]
* `ronin-1.5.0.rc2.gem`
  * **MD5:** `95746681d6cdbfd385bed63b43166b5f`
  * **SHA1:** `edc5e60fa415843f882802c8ef059ee37a8dd49e`
  * [PGP][5]
* `ronin-gen-1.2.0.rc2.gem`
  * **MD5:** `8bd309dccb32e585f0c2e585bb7ab29d`
  * **SHA1:** `ecc6efba1c674de73ea649b1051d76077c91ea44`
  * [PGP][6]

### ChangeLogs

* [ronin-support 0.5.0][7]
* [ronin 1.5.0][8]
* [ronin-gen 1.2.0][9]

### How Can You Help?

We would love your help testing these release candidates.
Here are some things you can do:

1. Install the Gems:

        $ gem install ronin-support ronin ronin-gen --pre

2. Test the new code, such as [Integer#pack], [Float#pack], [Array#pack],
  [String#unpack], [Ronin::Binary::Struct], [Ronin::Network::TCP::Proxy]
  ([example][10]) and [Ronin::Network::UDP::Proxy] ([example][11]).
3. Test the new commands, such as [ronin-net-proxy].
4. Review the new man-pages.

        $ ronin-help wordlist

5. Review the documentation:

        $ yard server -g -d
        $ $BROWSER http://localhost:8808/docs/ronin-support/0.5.0.rc2/frames
        $ $BROWSER http://localhost:8808/docs/ronin/1.5.0.rc2/frames
        $ $BROWSER http://localhost:8808/docs/ronin-gen/1.2.0.rc2/frames

[1]: http://rubygems.org/gems/ronin-support/versions/0.5.0.rc2
[2]: http://rubygems.org/gems/ronin/versions/1.5.0.rc2
[3]: http://rubygems.org/gems/ronin-gen/versions/1.2.0.rc2
[4]: https://github.com/downloads/ronin-rb/ronin-support/ronin-support-0.5.0.rc2.gem.asc
[5]: https://github.com/downloads/ronin-rb/ronin/ronin-1.5.0.rc2.gem.asc
[6]: https://github.com/downloads/ronin-rb/ronin-gen/ronin-gen-1.2.0.rc2.gem.asc
[7]: https://github.com/ronin-rb/ronin-support/blob/0.5.0/ChangeLog.md#050--2012-05-28
[8]: https://github.com/ronin-rb/ronin/blob/1.5.0/ChangeLog.md#150--2012-05-28
[9]: https://github.com/ronin-rb/ronin-gen/blob/1.2.0/ChangeLog.md#120--2012-05-28
[10]: https://gist.github.com/2657303
[11]: https://gist.github.com/2919927

[Integer#pack]: https://github.com/ronin-rb/ronin-support/blob/0.5.0/lib/ronin/formatting/extensions/binary/integer.rb#L90-127
[Float#pack]: https://github.com/ronin-rb/ronin-support/blob/0.5.0/lib/ronin/formatting/extensions/binary/float.rb#L24-49
[Array#pack]: https://github.com/ronin-rb/ronin-support/blob/0.5.0/lib/ronin/formatting/extensions/binary/array.rb#L26-51
[String#unpack]: https://github.com/ronin-rb/ronin-support/blob/0.5.0/lib/ronin/formatting/extensions/binary/array.rb#L26-51
[Ronin::Binary::Struct]: https://github.com/ronin-rb/ronin-support/blob/0.5.0/lib/ronin/binary/struct.rb#L26-49
[Ronin::Network::TCP::Proxy]: https://github.com/ronin-rb/ronin-support/blob/0.5.0/lib/ronin/network/tcp/proxy.rb#L27-76
[Ronin::Network::UDP::Proxy]: https://github.com/ronin-rb/ronin-support/blob/0.5.0/lib/ronin/network/udp/proxy.rb#L30
[ronin-net-proxy]: https://github.com/ronin-rb/ronin/blob/1.5.0/lib/ronin/ui/cli/commands/net/proxy.rb#L31-75
