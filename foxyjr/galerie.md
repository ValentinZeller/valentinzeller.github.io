---
layout: default
title: Galerie
---
<style>
    details {
        margin-top: 4px;
    }

    details summary:before {
        content: '• ';
    }

   details > summary {
  padding: 4px;
  width: 350px;
  background-color: #eeeeee;
  border: none;
  box-shadow: 1px 1px 2px #bbbbbb;
  cursor: pointer;
}

details > p {
  background-color: #eeeeee;
  padding: 4px;
  margin: 0;
  box-shadow: 1px 1px 2px #bbbbbb;
}

    details img {
        max-width: 200px !important;
    }
</style>


<details>
    <summary>Avatar</summary>
    {% for file in site.static_files | where: "image", true %}
        {% if file.path contains '/assets/img/avatar/'%}
            <a href="{{ file.path }}" target=_blank><img src="{{ file.path }}" alt="Gallery Image"/></a>
        {% endif %}
    {% endfor %}
</details>

<details>
    <summary>Bannière</summary>
        {% for file in site.static_files | where: "image", true %}
        {% if file.path contains '/assets/img/banniere/'%}
            <a href="{{ file.path }}" target=_blank><img src="{{ file.path }}" alt="Gallery Image"/></a>
        {% endif %}
    {% endfor %}
</details>

<details>
    <summary>Signature</summary>
        {% for file in site.static_files | where: "image", true %}
        {% if file.path contains '/assets/img/signature/'%}
            <a href="{{ file.path }}" target=_blank><img src="{{ file.path }}" alt="Gallery Image"/></a>
        {% endif %}
    {% endfor %}
</details>

<details>
    <summary>Fond d'écran</summary>
        {% for file in site.static_files | where: "image", true %}
        {% if file.path contains '/assets/img/fondecran/'%}
            <a href="{{ file.path }}" target=_blank><img src="{{ file.path }}" alt="Gallery Image"/></a>
        {% endif %}
    {% endfor %}
</details>

<details>
    <summary>Minecraft</summary>
    <details>
        <summary>Cité Octopus</summary>
        {% for file in site.static_files | where: "image", true %}
            {% if file.path contains '/assets/img/minecraft/citeoctopus/'%}
                <a href="{{ file.path }}" target=_blank><img src="{{ file.path }}" alt="Gallery Image"/></a>
            {% endif %}
        {% endfor %}
    </details>
        <details>
        <summary>Elements Perso</summary>
        {% for file in site.static_files | where: "image", true %}
            {% if file.path contains '/assets/img/minecraft/elementperso/'%}
                <a href="{{ file.path }}" target=_blank><img src="{{ file.path }}" alt="Gallery Image"/></a>
            {% endif %}
        {% endfor %}
    </details>
        <details>
        <summary>Jeux Hooplympique</summary>
        {% for file in site.static_files | where: "image", true %}
            {% if file.path contains '/assets/img/minecraft/jo/'%}
                <a href="{{ file.path }}" target=_blank><img src="{{ file.path }}" alt="Gallery Image"/></a>
            {% endif %}
        {% endfor %}
    </details>
        <details>
        <summary>Miniature Youtube</summary>
        {% for file in site.static_files | where: "image", true %}
            {% if file.path contains '/assets/img/minecraft/miniature/'%}
                <a href="{{ file.path }}" target=_blank><img src="{{ file.path }}" alt="Gallery Image"/></a>
            {% endif %}
        {% endfor %}
    </details>
        <details>
        <summary>Topic du Serveur Minecraft de Hooper</summary>
        {% for file in site.static_files | where: "image", true %}
            {% if file.path contains '/assets/img/minecraft/topic/'%}
                <a href="{{ file.path }}" target=_blank><img src="{{ file.path }}" alt="Gallery Image"/></a>
            {% endif %}
        {% endfor %}
    </details>
        <details>
        <summary>Autre</summary>
        {% for file in site.static_files | where: "image", true %}
            {% if file.path contains '/assets/img/minecraft/autre/'%}
                <a href="{{ file.path }}" target=_blank><img src="{{ file.path }}" alt="Gallery Image"/></a>
            {% endif %}
        {% endfor %}
    </details>
</details>

<details>
    <summary>Montage Silksong</summary>
        {% for file in site.static_files | where: "image", true %}
        {% if file.path contains '/assets/img/silksong/'%}
            <a href="{{ file.path }}" target=_blank><img src="{{ file.path }}" alt="Gallery Image"/></a>
        {% endif %}
    {% endfor %}
</details>

<details>
    <summary>Carte Mario Universalis</summary>
        {% for file in site.static_files | where: "image", true %}
        {% if file.path contains '/assets/img/cartemu/'%}
            <a href="{{ file.path }}" target=_blank><img src="{{ file.path }}" alt="Gallery Image"/></a>
        {% endif %}
    {% endfor %}
</details>
