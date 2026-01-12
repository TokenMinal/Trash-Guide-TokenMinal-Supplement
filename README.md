# Trash-Guide-TokenMinal-Supplement
To be used with Recyclarr. Allows the implementation of another CF to enhance the dectection of versioned release in the anime guide for filename following p2p naming. Also offer an Alternative to the Flux CF of the guide.

## Template available for this Supplement

This repository can be used with this repo:

* [Trash-Guide-TokenMinal-Supplement-Template](https://github.com/TokenMinal/Trash-Guide-TokenMinal-Supplement-Template)

## Available Custom Formats

### Radarr

* **Repack/Proper/v2**: `1eac3ab67b91433e9b934179f9d4c979`
* **Repack2 / v3**: `bd4ed93da52d423c8d6bf35bacc2def1`
* **Repack3 / v4**: `9a560df8bc2a4be980a4ccc1a23f5677`
* **Kitsune**: `fb140b19d962481aaf94517d289c5bed`

### Sonarr

* **Repack/Proper/v2**: `ea046366dc6845b69ff7338632ba5b5e`
* **Repack2 / v3**: `d7a5cc9eeeb84325829edaa95597cde9`
* **Repack3 / v4**: `f3ccad4373354f77915a37ba87e4da03`
* **Kitsune**: `9d710768cd914b59801641e278605262`
* **AnoZu**: `5e46e1f45b9948d4a65972512d314a22`
* **Cytox**: `ff77eb07c4554c2cb269f955dd96591d`


## Why this repo exist?
Here is why I made this supplement:

* **Group Preference**: The **Kitsune**,**AnoZu** and **Cytox** Custom Format are designed to prefer and prioritize these release group.
* **Different Repack Logic**: Standard TRaSH Guide logic uses two different CF for repacks and propers within Radarr and Sonarr. This supplement introduces a different logic in conjunction with the default one, with the default behaviour the anime guide can't make uses of REPACK to trigger upgrades. This fixes it, these Custom Formats will catch it and trigger the upgrade.

## Metadata Structure

The repository maintains a predictable structure for manual or automated mapping:

* **Radarr CFs**: `docs/json/radarr/cf/`
* **Sonarr CFs**: `docs/json/sonarr/cf/`

## License

This project is licensed under the MIT License - see the [LICENSE](https://www.google.com/search?q=LICENSE) file for details.
