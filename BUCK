# A list of available rules and their signatures can be found here: https://buck2.build/docs/prelude/globals/

genrule(
    name = "hello_world",
    out = "out.txt",
    cmd = "echo BUILT BY BUCK2> $OUT",
)

http_file(
  name = 'install-safe-chain',
  urls = [
    'https://github.com/AikidoSec/safe-chain/releases/download/1.5.29/install-safe-chain.sh',
  ],
  sha256 = 'e9bfa05430bca0efcf26e5a0f06d09b9da8cc21de2e0ffab03f512dde649ebbe',
  executable = True,
)

