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
                    <div class="d-flex mb-3 align-items-center">
                        <div class="fs-4 fw-bold flex-grow-1">
                            <a href="https://group.younited.com/">Younited</a>
                        </div>
                        <div class="fw-light text-end">
                            Développeur Senior <Date>10/2021 -</Date>
                        </div>
                    </div>

                    <div class="card-text p-2">
                        <div class="mb-2">
                            Younited est une solution de crédit à la consomation qui propose également une solution de
                            payment en plusieurs fois en ligne.
                        </div>

                        <Section title="Environnement" class="mb-2">
                            <div class="mx-3">
                                Au sein d'une équipe de 4 dévelppeurs, mon rôle a été de dévelpper de nouvelles
                                fonctionnalités afin d'automatiser les tâches opérationnelles de recouvrement ainsi que
                                d'assister aux tâches de support de la plateforme.
                            </div>
                        </Section>

                        <Section title="Missions">
                            <div class="row mx-4">
                                <ul class="col-8">
                                    <li>Création d'un système de réconciliation automatique des virements</li>
                                    <li>Intégration d'un système externe d'alerting</li>
                                    <li>Amélioration des processus automatiques de surendettement</li>
                                    <li>Mise en place d'un système de création automatique de contract afin d'accélérer les
                                        tests E2E back-end</li>
                                    <li>Fiabilisation du système de tests E2E front-end</li>
                                </ul>
                                <Cloud class="col-4 text-end" :words="[
                                    'C#', '.NET Core', 'Web API', 'CosmosDB', 'SQL Server', 'Azure', 'AppInsights', 'Azure Functions', 'Azure Service Bus', 'Angular', 'Big Query'
                                ]">
                                </Cloud>
                            </div>
                        </Section>
                    </div>
                </div>
            </div>

            <div class="card mb-3">
                <div class="card-body">
                    <div class="d-flex mb-3 align-items-center">
                        <div class="fs-4 fw-bold flex-grow-1">
                            <Mono>CSN</Mono> Energy
                        </div>
                        <div class="fw-light text-end">
                            Développeur Fullstack <Date>01/2019 - 09/2021</Date>
                        </div>
                    </div>
                    <div class="card-text p-2">
                        <div class="mb-2">
                            <Mono>CSN</Mono> Energy commercialise une plateforme SaaS permettant
                            la prise en charge complète d'une activité de fourniture d'énergie.
                        </div>

                        <Section title="Environnement" class="mb-2">
                            <div class="mx-3">
                                Au sein d'une équipe d'une dizaine de développeurs, mon rôle a été d'implémenter de
                                nouvelles fonctionnalités, mettre en place des solutions techniques, participer à la
                                conception d'une nouvelle architecture et assister aux tâches liées au DevOps.
                            </div>
                        </Section>

                        <Section title="Missions">
                            <div class="row mx-4">
                                <ul class="col-7">
                                    <li>Mise en place d'une architecture modulaire</li>
                                    <li>Intégration des services cloud d'Azure</li>
                                    <li>Développement d'outils internes</li>
                                    <li>Ajout de nouvelles fonctionnalités</li>
                                </ul>
                                <Cloud class="col-5 text-end" :words="[
                                    'C#', '.NET Framework', '.NET Core', 'Web API', 'OData', 'Swagger', 'SQL Server', 'Azure', 'Blob storage', 'AppInsights', 'Event Grid', 'Logic App', 'Kendo UI', 'VueJs'
                                ]">
                                </Cloud>
                            </div>
                        </Section>

                    </div>
                </div>
            </div>

            <div class="card mb-3">
                <h3 class="d-flex align-items-center card-header">
                    <div class="fs-3 fw-bold flex-grow-1">
                        <a href="https://www.viveris.fr/">Viveris</a>
                    </div>
                    <div class="fs-5 fw-light text-end">
                        Ingénieur Informatique <Date>12/2013 - 01/2019</Date>
                    </div>
                </h3>
                <div class="card-body">
                    <div>
                        Viveris est un groupe de conseil et d'ingénierie qui accompagne la transformation numérique des
                        entreprises et de leurs produits.
                    </div>
                    <hr>
                    <div class="mx-3">
                        <div class="card-text px-2">
                            <div class="d-flex mb-3 align-items-center">
                                <div class="fs-4 fw-bold flex-grow-1">
                                    <a href="https://www.ratp.fr/">
                                        <Mono>RATP</Mono>
                                    </a> - <Mono>OAM</Mono>
                                </div>
                                <div class="fw-light text-end">
                                    Lead Développeur <Date>2016 - 01/2019</Date>
                                </div>
                            </div>

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

                            <Section title="Mission">
                                <div class="row mx-4">
                                    <ul class="col-8">
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
                                    <Cloud class="col-4 text-end" :words="[
                                        'PHP', 'Zend', 'Symfony', 'Composer',
                                        'HTML', 'CSS', 'JavaScript', 'jQuery',
                                        'MySQL', 'scripting'
                                    ]">

                                    </Cloud>
                                </div>
                            </Section>

                        </div>

                        <hr>

                        <div class="card-text px-2">
                            <div class="d-flex mb-3 align-items-center">
                                <div class="fs-4 fw-bold flex-grow-1">
                                    <a href="https://www.medissimo.fr/">Medissimo</a>
                                </div>
                                <div class="fw-light text-end">
                                    Développeur Back-End <Date>2015-2016</Date>
                                </div>
                            </div>
                            <div>
                                Medissimo est une entreprise rattachée au milieu médical. Grâce à son logiciel informatique,
                                mis à disposition des pharmaciens, elle est leader mondial dans le domaine des piluliers.
                            </div>

                            <Section title="Environnement" class="mb-3">
                                <div class="mx-3">
                                    Au sein d'une équipe de 5 développeurs, j'ai été en charge de créer et mettre en place
                                    un back-end, pur Web API, permettant à l'application mobile de rappel de prise de
                                    médicament, de stocker et gérer les données des patients et de leurs aidants.
                                </div>
                            </Section>

                            <Section title="Missions">
                                <div class="row mx-4">
                                    <ul class="col-8">
                                        <li>Mise en place d'une nouvelle architecture</li>
                                        <li>Implémentation de Web API</li>
                                        <li>Intégration aux différents services de sécurité approuvés par l'état français
                                            pour
                                            la
                                            gestion de
                                            données médicales</li>
                                    </ul>
                                    <Cloud class="col-4 text-end" :words="[
                                        'C#', '.NET Framework',
                                        'Web API', 'WCF',
                                        'SQL Server',
                                        'AngularJs', 'jQuery'
                                    ]"></Cloud>
                                </div>
                            </Section>

                        </div>

                        <hr>

                        <div class="card-text px-2">
                            <div class="d-flex mb-3 align-items-center">
                                <div class="fs-4 fw-bold flex-grow-1">
                                    <a href="https://www.thalesgroup.com/fr">Thales</a>
                                </div>
                                <div class="fw-light text-end">
                                    Développeur Fullstack <Date>2014-2015</Date>
                                </div>
                            </div>
                            <Section title="Environnement" class="mb-3">
                                <div class="mx-3">
                                    Au sein d'une équipe de 5 développeurs, j'ai participé à la création du projet, la
                                    validation des choix technologiques et à l'implémentation des fonctionnalités jusqu'à
                                    leur première livraison.
                                </div>
                            </Section>

                            <Section title="Missions">
                                <div class="row mx-4">
                                    <ul class="col-8">
                                        <li>Validation des technologies front-end et de leur intégration back-end</li>
                                        <li>Implémentation d'une architecture MVC front-end avec RequireJs et DHTMLX</li>
                                        <li>Implémentation des fonctionnalités Back-End</li>
                                        <li>Mise en place de Selenium</li>
                                    </ul>
                                    <Cloud class="col-4 text-end" :words="[
                                        'C#', '.NET Framework', 'Asp.Net 4 MVC',
                                        'JavaScript', 'RequireJs', 'DHTMLX',
                                        'Oracle 11G'
                                    ]">
                                    </Cloud>
                                </div>
                            </Section>

                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>