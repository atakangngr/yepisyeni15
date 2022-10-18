<template>
  <NucGridPage v-bind:gap="{'col':0,'row':0}" v-bind:rows="[1]"
    v-bind:schema="{'r0-c0':{'col':0,'row':0,'showIn':['xs','sm','md','lg'],'colSpan':1,'rowSpan':1}}"
    v-bind:columns="[1]" overflow="auto" v-bind:designMode="false" v-bind:minNsLimit="0"
    v-bind:style="{'background':'#FFFFFF','paddingTop':'0px','paddingLeft':'0px','paddingRight':'0px','paddingBottom':'0px'}">
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="5a987edd-b28d-4b38-b5d6-5c24a8bb4df9" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'height':'auto','background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r0-c0" area="r0-c0">
      <WAspect
        src="https://quotefancy.com/media/wallpaper/800x450/1471043-Kapil-Dev-Quote-When-you-have-to-work-work-with-a-smile.jpg"
        tag="div" aspect="16:9"
        v-bind:aspects="[{'text':'4:3 (SD)','value':'4:3'},{'text':'1:1 (Square)','value':'1:1'},{'text':'16:9 (HD)','value':'16:9'},{'text':'1.85:1 (Widescreen)','value':'1.85:1'},{'text':'2:1 (Univisium/Superscope)','value':'2:1'},{'text':'21:9 (Anamorphic)','value':'21:9'},{'text':'1.43:1 (IMAX)','value':'1.43:1'},{'text':'3:2 (35mm Film)','value':'3:2'},{'text':'3:1 (APS-P)','value':'3:1'},{'text':'4/3 (Same as 4:3)','value':'4/3'},{'text':'16/9 (Same as 16:9)','value':'16/9'},{'text':'3 (Same as 3:1)','value':'3'},{'text':'2 (Same as 2:1)','value':'2'},{'text':'1.85 (Same as 1.85:1)','value':'1.85'},{'text':'1.5','value':'1.5'},{'text':'1 (Same as 1:1)','value':'1'}]"
        cardText="" bgVariant=""
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'src','displayName':'ImageUrl'},{'type':'string','propName':'cardText','displayName':'CardText'}]}"
        v-bind:textVisibility="true" position="absolute" top="33.55379746835443%" left="34.19239130434783%"
        id="ec6b4605-4f86-4191-896b-438a4b5bc0a0"
        v-bind:style="{'color':'#000000','width':'','fontSize':'6.755999999999999px','maxWidth':'','minWidth':'','fontStyle':'normal','marginTop':'','maxHeight':'','minHeight':'','textAlign':'left','background':'#ffffff','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','marginLeft':'','paddingTop':'','visibility':'visible','marginRight':'','paddingLeft':'','marginBottom':'','paddingRight':'','paddingBottom':'','textDecoration':'none','zIndex':2}"/>
      <WBlockButton tag="button" href="" v-bind:pill="false" size="md" text="Block Level Button" type="button"
        v-bind:block="true" color="" theme="theme--light01" v-bind:squared="false" variant="primary"
        v-bind:isEnabled="true" background="" linkTarget="_self" ncLinkType="link" borderColor="007BFF"
        ncTypography="body1" v-bind:resetTrigger="false" ncTooltipText="" verticalWidth="60px"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
        verticalHeight="60px" horizontalWidth="72.4479px" toForRouterLink="to" horizontalHeight="37.5347px"
        ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF" ncClickBorderColor="#007bff"
        ncDisableFontColor="#FFFFFF" ncFocusBorderColor="#007bff" ncHoverBorderColor="#007bff"
        ncDisableBorderColor="transparent" ncClickBackgroundColor="#007bff" ncFocusBackgroundColor="#007bff"
        ncHoverBackgroundColor="#007bff" ncDisableBackgroundColor="#969696" position="absolute"
        top="37.210443037974684%" left="0%" id="56dc777e-b906-471d-9038-4a05d5a97cac"
        v-bind:style="{'width':'','height':'','fontSize':'6.755999999999999px','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'center','fontFamily':'OpenSans-Bold,Open Sans','fontWeight':'bold','lineHeight':'0.7881999999999999','marginLeft':'0px','paddingTop':'','textShadow':'','visibility':'visible','borderStyle':'solid','marginRight':'0px','paddingLeft':'','marginBottom':'0px','paddingRight':'','paddingBottom':'','borderTopWidth':'0.563px','textDecoration':'none','borderLeftWidth':'0.563px','borderRightWidth':'0.563px','horizontalHeight':'21.132036099999997px','borderBottomWidth':'0.563px','borderTopLeftRadius':'2.252px','borderTopRightRadius':'2.252px','borderBottomLeftRadius':'2.252px','borderBottomRightRadius':'2.252px','zIndex':3}"/>
      <WDarkButton tag="button" href="" v-bind:pill="false" size="md" text="Dark" type="button" v-bind:block="false"
        color="" theme="theme--light01" v-bind:squared="false" variant="dark" v-bind:isEnabled="true" background=""
        linkTarget="_self" ncLinkType="link" borderColor="·#343A40" ncTypography="body1" v-bind:resetTrigger="false"
        ncTooltipText="" verticalWidth="60px"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
        verticalHeight="60px" horizontalWidth="72.4479px" toForRouterLink="to" horizontalHeight="37.5347px"
        ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF" ncClickBorderColor="#343a40"
        ncDisableFontColor="#FFFFFF" ncFocusBorderColor="#343a40" ncHoverBorderColor="#343a40"
        ncDisableBorderColor="transparent" ncClickBackgroundColor="#343a40" ncFocusBackgroundColor="#343a40"
        ncHoverBackgroundColor="#343a40" ncDisableBackgroundColor="#969696" position="absolute"
        top="29.621835443037973%" left="26.51304347826087%" id="cc56ec31-83f5-462d-8f2a-41dc314397fd"
        v-bind:style="{'width':'','height':'','fontSize':'6.755999999999999px','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'center','fontFamily':'OpenSans-Bold,Open Sans','fontWeight':'bold','lineHeight':'0.7881999999999999','marginLeft':'0px','paddingTop':'','textShadow':'','visibility':'visible','borderStyle':'solid','marginRight':'0px','paddingLeft':'','marginBottom':'0px','paddingRight':'','paddingBottom':'','borderTopWidth':'0.563px','textDecoration':'none','borderLeftWidth':'0.563px','borderRightWidth':'0.563px','horizontalHeight':'21.132036099999997px','borderBottomWidth':'0.563px','borderTopLeftRadius':'2.252px','borderTopRightRadius':'2.252px','borderBottomLeftRadius':'2.252px','borderBottomRightRadius':'2.252px','zIndex':4}"/>
    </NucGridCell>
  </NucGridPage>
</template>
<script>
export default {
  name: 'Screen1',
  data() {
    return {};
  },
  props: {},
  created() {},
  mounted() {},
  computed: {},
  methods: {},
  watch: {},
};
</script>

<style scoped></style>