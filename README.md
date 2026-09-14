# Phishing Detect

This directory contains the latest list of phishing websites. Users can download and query these data to improve security and protect against potential phishing attacks.

## Update Phishing Sites List

We will periodically update the phishing sites list to ensure data accuracy and timeliness. If you would like to suggest updates or provide feedback, you can submit issues or create a pull request with new phishing URLs.

## False-positive warnings and appeals

UniSat's phishing warning uses MetaMask's phishing list as its primary upstream source, with this repository providing supplemental data. As a result, a warning is often caused by an upstream MetaMask entry rather than by `phishing_sites.json`.

Before opening an issue here for a false positive:

1. Check whether the domain is in MetaMask's [active phishing list](https://raw.githubusercontent.com/MetaMask/eth-phishing-detect/main/src/config.json).
2. If it is listed, submit a removal request through MetaMask's [official issue tracker](https://github.com/MetaMask/eth-phishing-detect/issues/new/choose).
3. After MetaMask removes the entry, allow up to 24 hours for the updated list to synchronize to the UniSat extension.

Open an issue in this repository only when the warning remains after that synchronization window, or when you believe the warning comes from a UniSat-specific entry. Include the exact hostname, the MetaMask appeal link and status, and evidence that the site is legitimate. Do not share seed phrases, private keys, recovery phrases, passwords, or other secrets.

## Security Tips

- This list is provided for reference purposes, and detection methods for phishing sites may evolve over time.
- It is strongly recommended to use this list in conjunction with other security measures (e.g., antivirus software, network filters) to enhance protection.

## License

This project is licensed under the [MIT License](LICENSE).
