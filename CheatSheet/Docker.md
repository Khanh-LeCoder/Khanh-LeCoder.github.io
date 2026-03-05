To copy from local to container: docker cp /path/to/local [container-id]:/path/to/destination
To copy from container to local: docker cp [container-id]:/path/to/destination /path/to/local 

To remove file in containter: docker exec [container-id] rm -rf /path/to/file-or-directory

To change owner in container: docker exec [container-id] sudo chown -R /path/to/file-or-directory
To change group in container: docker exec [container-id] sudo chgrp -R /path/to/file-or-directory
