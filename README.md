Author(s): Montes Kato Alberto Daiji

Status: Draft

Ultima actualización: 15-10-2025

## Goals
- Localizar las 3 tiendas Oxxo mas cercanas en Ensenada desde un punto inicial.
- La busqueda en la base de datos sea precisa.
- Muestrear en un mapa usando las herramientas de Google.

## Non-Goals
- No habra marcado tiempo de llegada, solo orden del mas cercano al mas "lejano" de entre los 3.
- No se localizaran fuera de Ensenada.

## Background
Este proyecto ayudaria a usuarios a localizar la tienda mas cercana, pese a que en Mexico existen muchas tiendas muy cercanas, no muchos usuarios se atreven a ir a ciertas tiendas en alguna calle especifica,
esta herramienta sirve de alternativa para aquellos usuarios que no frecuentan cierto lugar o quienes buscan alternativas cercanas

## Overview
Este proyecto implementa:
- Base de datos con localizaciones de tiendas en Ensenada
- Una funcion que calcula la distancia entre el punto inicial y las tiendas (especificada en metros).
- Una funcion que entrega las 3 tiendas localizadas de menor a mayor distancia.
