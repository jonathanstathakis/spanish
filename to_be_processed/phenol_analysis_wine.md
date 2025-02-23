---
title: Analysis of Phenols for Wine Classification, Authentication
aliases:
  - wine phenol analysis
tags:
  - wine
  - vibrational_spectroscopy
  - phenols
  - phenol
  - non-flavonoids
  - nmr
  - GO
  - classification
  - authentication
  - analysis
type: zettel
cdt: 2024-07-18T13:47:50
mdt: 2024-07-22T12:50:01
---

# Wine Phenol Analysis

A note covering the analysis of [[phenols]] in [[wine]].

## Analysis of Phenols for Wine Classification

@merkytė_PhenolicCompoundsMarkers_2020, [sec. "4. Conclusions", pp. 29] write that phenol fingerprints can be used to judge quality and authenticity of a wine product.

## Techniques

### HPLC-MS

According to @popîrdă_ReviewRepresentativeMethods_2021, [sec. "2.2.1. Phenolic Compounds"], @jaitz_LCMSMS_2010, and @serrano-lourido_ClassificationcharacterisationSpanish_2012 demonstrated that wines could be classified by variety and geographic origin according to their phenolic profile.

TODO: continue extracting information from popîrda. What information? Quotables from each section.

## Markers

@popîrdă_ReviewRepresentativeMethods_2021, [sec. "2.2.1. Phenolic Compounds"] (citing @gonzález-neves_VarietaldifferentiationTannat_2007 @kallithraka_DifferentiationYoungRed_2007, @pavlousek-AuthenticationRieslingWines-2013) state that [[non_flavonoids|non-flavonoid]] [[phenols|phenolic compounds]] can be used as chemical markers for [[wine_go_authentication|wine geographical origin authentication]].

@merkytė_PhenolicCompoundsMarkers_2020, [sec. "4. Conclusions", pp. 29] provides a mapping of common markers for a given categorical variable.

@tzachristas_2020 [sec. "1. Introduction", pp. 2], citing @pasvanka_QualityToolsWine_2019, writes that specific phenolic compounds can be used as markers of authenticity.

### Anthocyanin

@popîrdă_ReviewRepresentativeMethods_2021, [sec. "2.2.1. Phenolic Compounds", pp. 7] describes Anthocyanins as an important class of markers of GO and variety, citing examples from Spain [@arozarena_DifferentiationSpanishwines_2000], Uruguay [@gonzález-neves_VarietaldifferentiationTannat_2007], China [@cheng_Anthocyanincharacteristicswines_2017]. and Eastern Europe [@geana_Verifyingredwines_2016].

### Phenolic Acids and Stilbenes

#### Phenolic Acids

@popîrdă_ReviewRepresentativeMethods_2021, [sec. "2.2.1. Phenolic Compounds", pp. 7] describes phenolic acids and stilbenes as being useful for classification by GO and variety, citing a Greek study [@kallithraka_DifferentiationYoungRed_2007]. They state that benzoic acid, gallic acid, vanillic acid and syringic acid, but also astringin, piceid and resveratrol were the best performing acidic markers.

Phenolic acids have been used as markers of authentication in white wine [@pasvanka_QualityToolsWine_2019].

#### Stilbenes

The best performing stilbenes as markers of GO are protocatechuic acid, p-hydroxybenzoic acid, caftaric acid, p-coutaric acid, trans and cis resveratrol, according to @popîrdă_ReviewRepresentativeMethods_2021, [sec. "2.2.1. Phenolic Compounds", pp. 7], citing @pavloušek_AuthenticationRieslingwines_2013.

### Vintage Year

Anthocyanins are the main marker used to observation of vintage year in red wines, and phenolic acids in white wine [@merkytė_PhenolicCompoundsMarkers_2020, sec. "4. Conclusions", pp. 29]

### Winemaking and Wooded Maturation

ellagic acids, phenolic acids, flavonols, tannins [@merkytė_PhenolicCompoundsMarkers_2020, sec. "4. Conclusions", pp. 29].

### Grape Variety

Phenolic acids, stilbenes (white wines), anthocyanins (red wines) [@merkytė_PhenolicCompoundsMarkers_2020, sec. "4. Conclusions", pp. 29].

### Detectors

[[liquid_chromatography|Liquid chromatography]] coupled to DAD or MS most common for general marker determination [@merkytė_PhenolicCompoundsMarkers_2020, sec. "4. Conclusions", pp. 29].

[[NMR]] and [[vibrational_spectroscopy|vibrational spectroscopy]] were are the most common detection method in geographical origin or vintage studies.

## Classification Modeling

### Dataset Size

Need a large dataset to capture all variation within the phenolic profile space [@merkytė_PhenolicCompoundsMarkers_2020, sec. "4. Conclusions", pp. 29].

### Specialised Models over Generalised

Due to the complexity of wine matrix and the high number of predictors of phenolic profile, generalised models are improbable, instead studies focus on models 'contextualised' (sic.) by defined factors and within the input dataset

### Statistical Analysis Techniques

PCA, LDA, PLS-DA, ANOVA are the most common models used [@merkytė_PhenolicCompoundsMarkers_2020, sec. "4. Conclusions", pp. 29].

### Optimizing Model

Regardless of variation from complexity of wine matrix and high number of predictors of phenol profile, success rates of over 90% can be achieved by 'calibrating' and selecting specific markers. [@merkytė_PhenolicCompoundsMarkers_2020, pp.29, sec. "4. Conclusions"]

## Research Interest

@merkytė_PhenolicCompoundsMarkers_2020, [sec. "4. Conclusions", pp. 29] observe that interest in the study of wine phenolic profiles has increased 'exponentially'.

## Research Gap

@merkytė_PhenolicCompoundsMarkers_2020, [sec. "4. Conclusions", pp. 29] note that in regard to quality control studies, the focus has been on red wines over white or rosé.

Link between individual markers and categorical variable is not clearly understood, possibly due in part to the fact that wine is a complex food matrix and that the phenolic profile is dependent on many factors @merkytė_PhenolicCompoundsMarkers_2020, [sec. "4. Conclusions", pp. 29].

## Disadvantages

@popîrdă_ReviewRepresentativeMethods_2021 [sec. "2.2.1. Phenolic Compounds", p. 8] refers to @tzachristas_PolyphenolsNaturalAntioxidants_2020 when stating that polyphenols are strongly predicted by "technology", authentication from the imprint "challanging", and that therefore phenol profile analysis cannot be used as a standalone authentication method.

## Related

[[phenol_profiles_are_instrument_specific]]  
[[categories_of_differentiation_of_wine_varietal_origin_vintage_vinification]].  
[[volatiles_non_volatiles_elements_isotopes_targeted_for_authentication]]  
[[most_authentication_studies_done_on_red_wine_rose_white_less_common]].  
[[classess_of_phenols_eligable_for_differentiation_of_wine]]  
[[phenolic_acids_used_differentiate_by_origin_white_wine]]  
[[flavonoids_anthocyanins_used_origin_differentiation_red_wine]]  
[[phenolic_acids_used_white_wine_diff_vintage]]  
[[anthocyanins_used_differentiate_red_wine_vintage]]  
[[list_of_targets_for_differentiation_by_vinification]]  
[[differentiation_by_varietal_targets_include_phenolic_acid_stilbenes_anthocyanins_red_white_wine]]  
[[high_number_of_predictors_of_phenolic_profile_make_creating_generalized_model_impossible]].  
[[studies_fail_to_rationalize_results_with_phenolic_profile_present]]  
[[large_sample_sizes_recommended_to_adequately_capture_all_variation_in_phenolic_profile_space]]
