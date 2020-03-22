# SearchMux

search engine multiplex server, e.g. for bang syntax

## Installation

Copy `searchmux` to a directory listed in `PATH`.

Dependencies are bash and sed.

## Usage

On a server with an open port, e.g. localhost:1492, run

```sh
$ searchmux 1492
```

and point your browser to <http(s)://localhost:1492> and enjoy.

## Configuration

Please run

```sh
searchmux --help`
```

and look into `searchmux`.


## License

Copyright (C) 2020  Johannes Rosenberger

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a [copy](LICENSE) of the GNU Affero General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
