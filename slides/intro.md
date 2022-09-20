# Understanding the structure of cities through the lens of data

##

<table>
    <col width="50%">
    <col width="50%">
    <tr>
        <td>
            <CENTER>
                <b>Martin Fleischmann</b>
            </CENTER>
        </td>
        <td>
            <CENTER>
                <b>James D. Gaboardi</b>
            </CENTER>
        </td>
    </tr>
    <tr>
        <td>
            <CENTER>
            <SMALL>
                <a href="https://twitter.com/martinfleis">@martinfleis</b></a>
            </SMALL>
            </CENTER>
        </td>
        <td>
            <CENTER>
            <SMALL>
                <a href="https://twitter.com/JamesGaboardi">@JamesGaboardi</b></a>
            </SMALL>
            </CENTER>
        </td>
    </tr>

</table>

<table>
    <col width="25%">
    <col width="25%">
    <col width="25%">
    <col width="25%">
    <tr>
        <td>
            <a href="https://www.liverpool.ac.uk/geographic-data-science/">
                <img src="fig/logo_liv.png" style="width:300px;vertical-align:middle;box-shadow:none">
            </a>
        </td>
        <td>
        <a href="http://urrlab.cz">
            <img src="fig/cuni.webp" style="width:300px;vertical-align:middle;box-shadow:none"></a>
        </td>
        <td>
        <a href="https://urbandatalab.ch">
            <img src="fig/udl.png" style="width:300;vertical-align:middle;box-shadow:none"></a>
        </td>
        <td>
        <a href="https://www.ornl.gov">
            <img src="fig/ornl.svg" style="width:300;vertical-align:middle;box-shadow:none"></a>
        </td>
    </tr>
</table>

#

## How we arrange "stuff" in cities matters

<table>
    <col width="50%">
    <col width="50%">
    <tr>
        <td>
            <CENTER>
                <img src="fig/nyt_buildings_dc.png" style="width:100%;vertical-align:middle">
            </CENTER>
        </td>

        <td>
            <CENTER>
                <img src="fig/nyt_buildings_mesa.png" style="width:100%;vertical-align:middle">
            </CENTER>
        </td>
    </tr>
</table>

<span class='pie'>Source: *A map of every building in America* ([New York
    Times](https://www.nytimes.com/interactive/2018/10/12/us/map-of-every-building-in-the-united-states.html))</span>

##

... it matters *a lot*

<table>
    <col width="33%" height="50%">
    <col width="33%" height="50%">
    <col width="33%" height="50%">
    <tr>
        <td>
            <CENTER>
                <img src="fig/joue_density.png" style="width:100%;vertical-align:middle">
            </CENTER>
        </td>

        <td>
            <CENTER>
                <img src="fig/cities_in_bad_shape.png" style="width:100%;vertical-align:middle">
            </CENTER>
        </td>

        <td>
            <CENTER>
                <img src="fig/est_emissions.png" style="width:100%;vertical-align:middle">
            </CENTER>
        </td>
    </tr>
    <tr class='fragment'>
        <td>
            <CENTER>
                <img src="fig/living_with_beauty.png" style="width:100%;vertical-align:middle">
            </CENTER>
        </td>

        <td>
            <CENTER>
                <img src="fig/oecd_rethinking_sprawl.png" style="width:100%;vertical-align:middle">
            </CENTER>
        </td>

        <td>
            <CENTER>
                <img src="fig/un_nua.png" style="width:100%;vertical-align:middle">
            </CENTER>
        </td>
    </tr>
</table>

#

## Urban Form

<CENTER>
    *What does it look like?*
</CENTER>

<CENTER>
    <span class='fragment' style='color:#3b6e8c'>
        "Physical structure and appearance of cities"
    </span>
</CENTER>

## What do we talk about

<CENTER>
    <span class='fragment' style='color:#3b6e8c'>
        ... when we talk about urban morphology?
    </span>
</CENTER>
<br />
<table>
    <col width="25%">
    <col width="25%">
    <col width="25%">
    <col width="25%">
    <tr>
        <td style="vertical-align:middle">
            <CENTER>
                <span class='fragment'>
                    buildings
                </span>
            </CENTER>
        </td>
        <td style="vertical-align:middle">
            <CENTER>
                <span class='fragment'>
                    streets
                </span>
            </CENTER>
        </td>
        <td style="vertical-align:middle">
            <CENTER>
                <span class='fragment'>
                    plots
                </span>
            </CENTER>
        </td>
        <td style="vertical-align:middle">
            <CENTER>
                <span class='fragment'>
                    open spaces
                </span>
            </CENTER>
        </td>
    </tr>
</table>

## How can we describe it

<CENTER>
    <span class='fragment' style='color:#3b6e8c'>
        ... numerically?
    </span>
</CENTER>

## Urban morphometrics

<CENTER>
    <span class='fragment' style='color:#3b6e8c'>
        "quantitative analysis of urban form"
    </span>
</CENTER>

<br />
<CENTER>
    <span class='fragment'>
        All about <span class='hlg'>measuring</span>.
    </span>
</CENTER>

## Measuring

<table>
    <col width="33%">
    <col width="33%">
    <col width="33%">
    <tr>
        <td style="vertical-align:middle">
            <CENTER>
                <span class='fragment'>
                    dimension
                </span>
            </CENTER>
        </td>
        <td style="vertical-align:middle">
            <CENTER>
                <span class='fragment'>
                    shape
                </span>
            </CENTER>
        </td>
        <td style="vertical-align:middle">
            <CENTER>
                <span class='fragment'>
                    spatial distribution
                </span>
            </CENTER>
        </td>
    </tr>
    <tr>
        <td style="vertical-align:middle">
            <CENTER>
                <span class='fragment'>
                    intensity
                </span>
            </CENTER>
        </td>
        <td style="vertical-align:middle">
            <CENTER>
                <span class='fragment'>
                    connectivity
                </span>
            </CENTER>
        </td>
        <td style="vertical-align:middle">
            <CENTER>
                <span class='fragment'>
                    diversity
                </span>
            </CENTER>
        </td>
    </tr>
</table>

## Why?

<CENTER>
    <span class='fragment'>
        Because we (finally) can!
    </span>
</CENTER>

## Data

<CENTER>
    <span class='fragment'>
        <img src="fig/osm.png" style="width:100%;vertical-align:middle;box-shadow:none">
    </span>
</CENTER>

## Tools

<table>
    <col width="33%">
    <col width="33%">
    <col width="33%">
    <tr>
        <td>
            <CENTER>
                <span class='fragment'>
                    GeoPandas
                </span>
            </CENTER>
        </td>
        <td>
            <CENTER>
                <span class='fragment'>
                    PySAL
                </span>
            </CENTER>
        </td>
        <td>
            <CENTER>
                <span class='fragment'>
                    momepy
                </span>
            </CENTER>
        </td>
    </tr>
</table>

## GeoPandas

<CENTER>
    <span class='fragment' style='color:#3b6e8c'>
        GeoPandas is an open source project to add support for geographic data to pandas objects.
    </span>
</CENTER>
<br />
<CENTER>
    <span class='fragment'>
        <a href="https://geopandas.org">geopandas.org</a>
    </span>
</CENTER>

## PySAL

<CENTER>
    <span class='fragment' style='color:#3b6e8c'>
        Python Spatial Analysis Library
    </span>
</CENTER>
<br />
<CENTER>
    <span class='fragment'>
        <a href="https://pysal.org">pysal.org</a>
    </span>
</CENTER>

## momepy

<CENTER class='fragment' >
    <span style='color:#3b6e8c'>
        Urban Morphology Measuring Toolkit
    </span>
    <small>
A member of the PySAL family
</small>
</CENTER>
<CENTER>
    <span class='fragment'>
        <a href="https://momepy.org">momepy.org</a>
    </span>
</CENTER>

#

## Outline

<CENTER>
    <span class='fragment'>
        <img src="fig/workflow.png" style="width:100%;vertical-align:middle;box-shadow:none">
    </span>
</CENTER>
