# fs_service

Template of a C++ service that uses [userver framework](https://github.com/userver-framework/userver) with PostgreSQL and storage_cpp.


## Download and Build

To make it work(create debug version):

1. In "fs_service" directory just run `make`

## Run service

0. Create Postgres database and configure "./configs/config_vars.yaml"
1. In "fs_service" directory run:
`./build_debug/fs_service -c ./configs/static_config.yaml`
2. Use console and "help_file.txt" to check the work of service
3. Use Ctrl+C to finish service (I didn't found out another way)

## License

I didn't touch it. Let it stay as it is.

The original template is distributed under the [Apache-2.0 License](https://github.com/userver-framework/userver/blob/develop/LICENSE)
and [CLA](https://github.com/userver-framework/userver/blob/develop/CONTRIBUTING.md). Services based on the template may change
the license and CLA.
