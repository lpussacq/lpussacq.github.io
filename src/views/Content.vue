<script setup lang="ts">
import Cloud from '@/components/Cloud.vue'
import Mono from '@/components/Mono.vue';
import Date from '@/components/Date.vue';
import Section from '@/components/Section.vue';
</script>

<template>
    <div class="text-primary-emphasis">
        <div>
            <div class="text-center">
                <h1>Lucas PUSSACQ</h1>
                <h2>Ingénieur Informatique</h2>
            </div>

            <div>
                <h3>Formations</h3>
                <ul>
                    <li>
                        <Date>2013</Date> - <a href="https://www.iit.edu/">
                            <Mono>IIT</Mono>
                        </a> -
                        Master in Computer Science
                    </li>
                    <li>
                        <Date>2013</Date> - <a href="https://www.bordeaux-inp.fr/fr">
                            <Mono>INP</Mono>
                        </a> - <a href="https://enseirb-matmeca.bordeaux-inp.fr/fr"><span>ENSEIRB-Matmeca</span></a> -
                        Ingénieur en informatique
                    </li>
                    <li>
                        <Date>2010</Date> - <a href="https://www.iut.u-bordeaux.fr/info/">
                            <Mono>IUT</Mono>
                        </a> - <Mono>DUT</Mono> en
                        informatique
                    </li>
                </ul>
            </div>

            <div class="card mb-3">
                <div class="card-body">
                    <h5 class="card-title">
                        <a href="https://younited.com/group">Younited</a>
                    </h5>
                    <h6 class="card-subtitle mb-2 text-body-secondary">
                        Développeur Senior <Date>09/2021 -</Date>
                    </h6>
                    <div class="card-text p-2">
                        <div class="mb-2">
                            Younited est une solution de crédit. 
                        </div>

                        <Section title="Environnement" class="mb-2">
                            <div class="mx-3">
                                
                            </div>
                        </Section>

                        <div class="row">
                            <Section title="Missions" class="col-7">
                                <ul>
                                    <li>Mise en place d'une architecture modulaire</li>
                                
                                </ul>
                            </Section>

                            <Section title="Technologies" class="col-5 text-end">
                                <Cloud class="text-end" :words="[
                            'C#', '.NET Core', 'Web API', 'OData', 'CosmosDB', 'SQL Server', 'AppInsights', 'Azure Functions', 'Azure Service Bus', 'Angular', 'Big Query'
                                ]">
                                </Cloud>
                            </Section>
                        </div>
                    </div>
                </div>
            </div>

            <div class="card mb-3">
                <div class="card-body">
                    <h5 class="card-title">
                        <Mono>CSN</Mono> Energy
                    </h5>
                    <h6 class="card-subtitle mb-2 text-body-secondary">
                        Ingénieur Informatique <Date>01/2019 - 09/2021</Date>
                    </h6>
                    <div class="card-text p-2">
                        <div class="mb-2">
                            <Mono>CSN</Mono> Energy commercialise une plateforme SaaS permettant
                            la prise en charge complète d'une activité de fourniture d'énergie.
                        </div>

                        <Section title="Environnement" class="mb-2">
                            <div class="mx-3">
                                Au sein d'une équipe d'une dizaine de développeurs, mon rôle a été d'implémenter de nouvelles fonctionnalités, mettre en place des solutions techniques, participer à la conception d'une nouvelle architecture et assister aux tâches liées au DevOps.
                            </div>
                        </Section>

                        <div class="row">
                            <Section title="Missions" class="col-7">
                                <ul>
                                    <li>Mise en place d'une architecture modulaire</li>
                                    <li>Intégration des services cloud d'Azure</li>
                                    <li>Développement d'outils internes</li>
                                    <li>Ajout de nouvelles fonctionnalités</li>
                                </ul>
                            </Section>

                            <Section title="Technologies" class="col-5 text-end">
                                <Cloud class="text-end" :words="[
                            'C#', '.NET Framework', '.NET Core','Web API', 'OData', 'Swagger', 'SQL Server','Azure', 'Blob storage', 'AppInsights', 'Event Grid', 'Function App', 'Logic App', 'Kendo UI', 'VueJs'
                                ]">
                                </Cloud>
                            </Section>
                        </div>
                    </div>
                </div>
            </div>

            <div class="card mb-3">
                <h3 class="card-header"><a href="https://www.viveris.fr/">Viveris</a></h3>
                <div class="card-body">
                    <h4 class="card-title">
                        Ingénieur Informatique <Date>12/2013 - 01/2019</Date>
                    </h4>
                    <div>
                        Viveris est un groupe de conseil et d'ingénierie qui accompagne la transformation numérique des
                        entreprises et de leurs produits.
                    </div>
                    <hr>
                    <div class="mx-3">
                        <div class="card-text px-2">
                            <h5 class="card-title">
                                <a href="https://www.ratp.fr/">
                                    <Mono>RATP</Mono>
                                </a> - <Mono>OAM</Mono>
                            </h5>
                            <h6 class="card-subtitle mb-2 text-body-secondary">
                                Lead Développeur <Date>2016 - 01/2019</Date>
                            </h6>
                            <div>
                                Au sein de la <Mono>RATP</Mono>, l'entité <Mono>OAM</Mono> (Outils d'Aide à la Maintenance)
                                développe des solutions logicielles permettant de faciliter le maintien du parcs
                                d'équipements présents dans les stations de la société de transport.
                            </div>

                            <Section title="Environnement">
                                <div class="mx-3">
                                    Au sein d'une équipe de 6 développeurs, mon rôle a été d'ajouter de nouvelles
                                    fonctionnalités et de maintenir l'application de télémaintenance et télédiagnostique
                                    "Audace".
                                </div>
                            </Section>

                            <div class="row">
                                <Section title="Mission" class="col-7">
                                    <ul>
                                        <li>
                                            Ajout de fonctionnalités (télédiagnostique, télémaintenance, état du parc, ...)
                                        </li>
                                        <li>
                                            Migration de <Mono>PHP</Mono> 5.6 vers <Mono>PHP</Mono> 7.1
                                        </li>
                                        <li>
                                            Migration de Zend 1.12 vers Symfony 3.4
                                        </li>
                                        <li>
                                            Création d'une nouvelle application extranet (mobile first)
                                        </li>
                                    </ul>
                                </Section>

                                <Section title="Technologies" class="col-5 text-end">
                                    <Cloud class="text-end" :words="[
                                        'PHP', 'Zend', 'Symfony', 'Composer',
                                        'HTML', 'CSS', 'JavaScript', 'jQuery',
                                        'MySQL', 'scripting'
                                    ]">

                                    </Cloud>
                                </Section>
                            </div>
                        </div>

                        <hr>

                        <div class="card-text px-2">
                            <h5 class="card-title">
                                <a href="https://www.medissimo.fr/">Medissimo</a>
                            </h5>
                            <h6 class="card-subtitle mb-2 text-body-secondary">
                                Développeur Back-End <Date>2015-2016</Date>
                            </h6>
                            <div>
                                Medissimo est une entreprise rattachée au milieu médical. Grâce à son logiciel informatique,
                                mis à disposition des pharmaciens, elle est leader mondial dans le domaine des piluliers.
                            </div>

                            <Section title="Environnement">
                                <div class="mx-3">
                                    Au sein d'une équipe de 5 développeurs, j'ai été en charge de créer et mettre en place
                                    un back-end, pur Web API, permettant à l'application mobile de rappel de prise de
                                    médicament, de stocker et gérer les données des patients et de leurs aidants.
                                </div>
                            </Section>

                            <div class="row">
                                <Section title="Missions" class="col-7">
                                    <ul>
                                        <li>Mise en place d'une nouvelle architecture</li>
                                        <li>Implémentation de Web API</li>
                                        <li>Intégration aux différents services de sécurité approuvés par l'état français
                                            pour
                                            la
                                            gestion de
                                            données médicales</li>
                                    </ul>
                                </Section>

                                <Section title="Technologies" class="col-5 text-end">
                                    <Cloud :words="[
                                        'C#', '.NET Framework',
                                        'Web API', 'WCF',
                                        'SQL Server',
                                        'AngularJs', 'jQuery'
                                    ]"></Cloud>
                                </Section>
                            </div>
                        </div>

                        <hr>

                        <div class="card-text px-2">
                            <h5 class="card-title">
                                <a href="https://www.thalesgroup.com/fr">Thales</a>
                            </h5>
                            <h6 class="card-subtitle mb-2 text-body-secondary">
                                Développeur Back-End/Front-End <Date>2014-2015</Date>
                            </h6>
                            <Section title="Environnement">
                                <div class="mx-3">
                                    Au sein d'une équipe de 5 développeurs, j'ai participé à la création du projet, la
                                    validation des choix technologiques et à l'implémentation des fonctionnalités jusqu'à
                                    leur première livraison.
                                </div>
                            </Section>

                            <div class="row">
                                <Section title="Missions" class="col-8">
                                    <ul>
                                        <li>Validation des technologies front-end et de leur intégration back-end</li>
                                        <li>Implémentation d'une architecture MVC front-end avec RequireJs et DHTMLX</li>
                                        <li>Implémentation des fonctionnalités Back-End</li>
                                        <li>Mise en place de Selenium</li>
                                    </ul>
                                </Section>

                                <Section title="Technologies" class="col-4" style="direction: rtl;">
                                    <Cloud :words="[
                                        'C#', '.NET Framework', 'Asp.Net 4 MVC',
                                        'JavaScript', 'RequireJs', 'DHTMLX',
                                        'Oracle 11G'
                                    ]">
                                    </Cloud>
                                </Section>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>