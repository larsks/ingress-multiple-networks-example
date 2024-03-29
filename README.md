Inspired by <https://serverfault.com/questions/1157086/is-is-possible-to-configure-two-external-ip-addresses-to-an-nginx-ingress-contro>.

**WARNING** You will need to modify the ip addresses used in this example before it will work in your environment.

To deploy:

1. Install metallb:

    ```
    kubectl apply -k metallb
    ```

1. Install everything else:

    ```
    kubectl apply -k .
    ```
