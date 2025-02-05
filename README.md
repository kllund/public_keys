# Repository for kllund's public keys

To add a public key to your list of authorized users (on *NIX), run the following command:

`curl https://raw.githubusercontent.com/kllund/public_keys/refs/heads/main/NAME_OF_KEY_id_rsa.pub >> ~/.ssh/authorized_keys`

Example:

`curl https://raw.githubusercontent.com/kllund/public_keys/refs/heads/main/kllund_kllundnano_id_rsa.pub >> ~/.ssh/authorized_keys`
