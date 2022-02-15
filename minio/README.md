### Running minio server

Use the following command to run a standalone MinIO server on macOS. Replace ``/data`` with the path to the drive or directory in which you want MinIO to store data.

```sh
./minio server /data
```

The MinIO deployment starts using default root credentials `minioadmin:minioadmin`. You can test the deployment using the MinIO Console, an embedded web-based object browser built into MinIO Server. Point a web browser running on the host machine to <http://127.0.0.1:9000> and log in with the root credentials. You can use the Browser to create buckets, upload objects, and browse the contents of the MinIO server.

You can also connect using any S3-compatible tool, such as the MinIO Client `mc` commandline tool. See [Test using MinIO Client `mc`](#test-using-minio-client-mc) for more information on using the `mc` commandline tool. For application developers, see <https://docs.min.io/docs/> and click **MinIO SDKs** in the navigation to view MinIO SDKs for supported languages.
